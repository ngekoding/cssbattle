# Battle #1 - Pilot Battle

## #3 - Push Button

[Link to the problem](https://cssbattle.dev/play/3)

[result]: ./images/3-push-button.png

```html
<div class="wrapper">
  <div class="circle circle-outer"></div>
  <div class="circle circle-center"></div>
</div>
<style>
  body {
    background: #6592CF;
  }
  .wrapper {
    width: 300px;
    height: 150px;
    background: #243D83;
    margin: 75px auto;
    position: relative;
  }
  .circle {
    border-radius: 50%;
  }
  .circle-outer {
    position: absolute;
    left: 25px;
    top: -50px;
    width: 250px;
    height: 250px;
    background: transparent;
    box-sizing: border-box;
    border: 50px solid #6592CF;
  }
  .circle-center {
    position: absolute;
    width: 50px;
    height: 50px;
    left: 125px;
    top: 50px;
    background: #EEB850;
  }
</style>
```