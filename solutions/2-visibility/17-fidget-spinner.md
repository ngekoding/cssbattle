# Battle #2 - Visibility

## #17 - Fidget Spinner

[Link to the problem](https://cssbattle.dev/play/17)

![result](./images/17-fidget-spinner.png)

```html
<div class="circle"></div>
<div class="rectangle"></div>
<div class="circle"></div>
<div class="circle2 top"></div>
<div class="circle2 bottom"></div>
<style>
  body {
    background: #09042A;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    width: 80px;
    height: 80px;
    box-sizing: border-box;
    border: 10px solid #E78481;
    border-radius: 50%;
  }
  .rectangle {
    width: 60px;
    height: 50px;
    background: #E78481;
    margin-left: -10px;
    margin-right: -10px;
    border-radius: -50px;
  }
  .circle2 {
    position: absolute;
    width: 80px;
    height: 80px;
    background: #F5BB9C;
    border-radius: 50%;
    border: 10px solid #09042A;
    box-sizing: border-box;
  }
  .circle2.top {
    top: 57.2px;
  }
  .circle2.bottom {
    bottom: 57.2px;
  }
</style>
```