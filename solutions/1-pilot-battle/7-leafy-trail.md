# Battle #1 - Pilot Battle

## #7 - Leafy Trail

[Link to the problem](https://cssbattle.dev/play/7)

[result]: ./images/7-leafy-trail.png

```html
<div class="wrapper">
  <div class="leaf"></div>
  <div class="leaf"></div>
  <div class="leaf"></div>
</div>
<style>
  body {
    background: #0B2429;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .wrapper {
    position: relative;
    height: 150px;
    width: 250px;
  }
  .leaf:first-child {
    left: 0;
	background: #1A4341;
  }
  .leaf:nth-child(2) {
    left: 50px;
	background: #998235;
  }
  .leaf:nth-child(3) {
    left: 100px;
	background: #F3AC3C;
  }
  .leaf {
    position: absolute;
    width: 150px;
    height: 150px;
    border-top-left-radius: 67%;
    border-bottom-right-radius: 67%;
  }
</style>
```