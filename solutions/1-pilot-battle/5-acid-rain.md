# Battle #1 - Pilot Battle

## #5 Acin Rain

[Link to the problem](https://cssbattle.dev/play/5)

[result]: ./images/5-acid-rain.png

```html
<div class="wrapper">
  <div class="c c-1"></div>
  <div class="c c-2"></div>
  <div class="c c-3"></div>
</div>
<style>
  body {
    background: #0B2429;
  }
  .wrapper {
    display: flex;
    height: 240px;
    margin: 30px auto;
  }
  .c {
    width: 120px;
    height: 120px;
    background: #F3AC3C;
    border-radius: 50%;
    border-top-right-radius: 0;
    margin-left: -60px;
  }
  .c-1 {
    align-self: flex-end;
    z-index: 3;
    margin-left: 72px;
  }
  .c-2 {
    background: #998235;
    align-self: center;
    z-index: 2;
  }
  .c-3 {
    transform: rotate(180deg);
  }
</style>
```