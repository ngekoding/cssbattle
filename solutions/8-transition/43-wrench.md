# Battle #8 - Transition

## #43 - Wrench

[Link to the problem](https://cssbattle.dev/play/43)

![result](./images/43-wrench.png)

```html
<div></div>
<div></div>
<style>
  body {
    background: #6592CF;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 70px;
    height: 242px;
    box-sizing: border-box;
    border: 30px solid #243D83;
    border-left: 0;
    border-top-right-radius: 100px;
    border-bottom-right-radius: 100px;
    margin-top: 2px;
  }
  div:nth-child(2) {
    transform: scaleX(-1);
    margin-left: -30px;
  }
</style>
```