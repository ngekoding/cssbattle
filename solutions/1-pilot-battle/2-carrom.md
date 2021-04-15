# Battle #1 - Pilot Battle

## #2 - Carrom

[Link to the problem](https://cssbattle.dev/play/2)

![result](./images/2-carrom.png)

```html
<div class="wrapper">
  <div class="box top-left"></div>
  <div class="box top-right"></div>
  <div class="box bottom-left"></div>
  <div class="box bottom-right"></div>  
</div>
<style>
  body {
    background: #62374e;
  }
  .wrapper {
    width: 300px;
    height: 200px;
    margin: 50px auto;
    position: relative;
  }
  .box {
    width: 50px;
    height: 50px;
    background: #fdc57b;
    position: absolute;
  }
  .box.top-right {
    right: 0
  }
  .box.bottom-left {
    bottom: 0;
  }
  .box.bottom-right {
    bottom: 0;
    right: 0;
  }
</style>
```