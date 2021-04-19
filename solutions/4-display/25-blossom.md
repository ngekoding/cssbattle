# Battle #4 - Display

## #25 - Blossom

[Link to the problem](https://cssbattle.dev/play/25)

![result](./images/25-blossom.png)

```html
<div class="wrap">
  <div class="leaf-lg t l"></div>
  <div class="leaf-lg b r flip-x"></div>
  <div class="leaf-sm t r flip-x"></div>
  <div class="leaf-sm b l"></div>
</div>
<style>
  body {
    background: #998235;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .wrap { 
    width: 180px; 
    height: 180px;
    position: relative;
  }
  .t { top: 0 }
  .b { bottom: 0 }
  .r { right: 0 }
  .l { left: 0 }
  .flip-x { transform: scaleX(-1) }
  .leaf-lg, .leaf-sm {
    position: absolute;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
  }
  .leaf-lg {
    width: 80px;
    height: 100px;
    background: #1A4341;
  }
  .leaf-sm {
    width: 80px;
    height: 60px;
    background: #F3AC3C;
  }
</style>
```