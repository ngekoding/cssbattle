# Battle #2 - Visibility

## #15 - Overlap

[Link to the problem](https://cssbattle.dev/play/15)

![result](./images/15-overlap.png)

```html
<div class="circle"></div>
<div class="circle"></div>
<div class="center"></div>
<style>
  body {
    background: #09042A;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    background: #7B3F61;
    width: 150px;
    height: 150px;
    border-radius: 50%;
  }
  .circle:first-child {
    margin-right: -50px;
  }
  .circle:nth-child(2) {
    background: #E78481;
  }
  .center {
    position: absolute;
    width: 80px;
    height: 80px;
    background: #09042A;
    transform: rotate(45deg);
    border-top-right-radius: 75px;
    border-bottom-left-radius: 75px;
  }
</style>
```