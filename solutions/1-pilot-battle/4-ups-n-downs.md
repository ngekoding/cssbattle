# Battle #1 - Pilot Battle

## #4 - Ups n Downs

[Link to the problem](https://cssbattle.dev/play/4)

[result]: ./images/4-ups-n-downs.png

```html
<div class="wrapper">
  <div class="box1"></div>
  <div class="box2"></div>
  <div class="box3"></div>
</div>
<style>
  body {
    background: #62306D;
  }
  .wrapper {
    width: 100%;
    height: 200px;
    margin-top: 50px;
    display: flex;
    justify-content: center;
  }
  div[class^='box'] {
    background: #F7EC7D;
    height: 100px;
    width: 100px;
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%;
  }
  .box1, .box3 {
    align-self: flex-end;
  }
  .box2 {
    transform: rotate(180deg)
  }
</style>

```