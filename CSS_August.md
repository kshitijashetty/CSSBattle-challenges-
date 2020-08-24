[#29](https://cssbattle.dev/play/29)
```html
<div class="wrapper">
  <div class="container">
    <div class="sector top-left"></div>
    <div class="sector top-right"></div>
    <div class="sector bottom-left"></div>
    <div class="sector bottom-right"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #F3AC3C;
    display:grid;
    place-items:center;
  }
  .container{
    width:200px;
    height:200px;
    display:flex;
    background:#1A4341;
  }
  .sector{
    width:100px;
    height:100px;
    background:#F3AC3C;
    border-radius:100% 0 0 0;
  }
  .top-left{
    position:absolute;
    transform:rotate(-180deg);
  }
  .top-right{
    position:absolute;
    right:100px;
    transform:rotate(-90deg);
  }
  .bottom-left{
    position:absolute;
    bottom:50px;
    transform:rotate(-270deg);
  }
  .bottom-right{
    position:absolute;
    bottom:50px;
    right:100px
  }
</style>
```

[#30](https://cssbattle.dev/play/30)
```html
<div class="yellow"></div>
<div class="brown"></div>
<div class="pink"></div>
<div class="purple"></div>
<style>
  body{
    margin:0;
  }
  .yellow {
    width: 400px;
    height: 50px;
    background: #F7EC7D;
  }
  .brown{
    width:400px;
    height:50px;
    background:#E38F66;
  }
  .pink{
    width:400px;
    height:100px;
    background:#AA445F;
  }
  .purple{
    width:400px;
    height:100px;
    background:#62306D
  }
</style>
```

[#31](https://cssbattle.dev/play/31)
```html
<div class="wrapper">
  <div class="circle left"></div>
  <div class="rectangle"></div>
  <div class="circle right"></div>
</div>
<style>
  body{
    margin:0;
  }
 .wrapper {
    width: 400px;
    height: 300px;
    background: #AA445F;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .circle{
    width:100px;
    height:200px;
    
    border-bottom-left-radius: 200px;
    border-top-left-radius:200px;
  }
  .left{
    background:#F7EC7D;
  }
  .right{
    background:#E38F66;
    transform:rotate(-180deg)
  }
  .rectangle{
    height:200px;
    width:50px;
  }
</style>

```

[#32](https://cssbattle.dev/play/32)
```html
<div class="wrapper">
  <div class="container">
    <div class="green"></div>
    <div class="center">
      <div class="yellow"></div>
      <div class="square"></div>
      <div class="yellow"></div>
    </div>
    <div class="green"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
 .wrapper {
    width: 400px;
    height: 300px;
    background: #FFFFFF;
    display:grid;
    place-items:center;
  }
  .container{
    display:grid;
    place-items:center;
    transform:rotate(45deg);
  }
  .green{
    height:75px;
    width:50px;
    background:#A3A368;
  }
  .center{
    height:50px;
    width:200px;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .yellow{
    height:50px;
    width:75px;
    background:#F3AC3C;
  }
  .square{
    height:50px;
    width:50px;
    background:#FBE18C;
  }
</style>
```


[]()
```html

```

[]()
```html

```

[]()
```html

```


[]()
```html

```

[]()
```html

```

[]()
```html

```
