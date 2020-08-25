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


[#33](https://cssbattle.dev/play/33)
```html
<div class="wrapper">
  <div class="semi">
    <div class="circle"></div>
  </div>
  <div class="sector"></div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .semi{
    height:150px;
    width:75px;
    background:#998235;
    border-top-left-radius:150px;
    border-bottom-left-radius:150px;
    position:relative;
    left:10px;
  }
  .sector{
    height:100px;
    width:100px;
    background:#F3AC3C;
    border-radius:0px 100% 0px 0px;
    position:relative;
    bottom:50px;
    left:10px;
  }
  .circle{
    height:30px;
    width:30px;
    border-radius:50%;
    background-color:#0B2429;
    position:relative;
    left:30px;
    top:30px;
  }
</style>
```

[#34](https://cssbattle.dev/play/34)
```html
<div class="wrapper">
  <div class="triangle one"></div>
  <div class="triangle two"></div>
  <div class="triangle three"></div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #007065;
    display:grid;
    place-items:center;
  }
  .triangle{
    width:0px;
    height:0px;
    border-left:125px solid transparent;
    border-right:125px solid transparent;
  }
  .one{
    z-index:1;
    border-bottom:100px #FFEECF solid;
    position:relative;
    top:50px;
  }
  .two{
    border-bottom:100px #00A79D solid;
    position:relative;
    top:50px;
  }
  .three{
    border-bottom:100px #F5C181 solid;
    position:relative;
    bottom:100px;
  }
</style>
```

[#35](https://cssbattle.dev/play/35)
```html
<div class="wrapper">
  <div class="icecream"></div>
  <div class="logo"></div>
  <div class="stick"></div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #293462;
    display:grid;
    place-items:center;
  }
  .icecream{
    width:100px;
    height:150px;
    background:#FFF1C1;
    border-top-left-radius: 100px;
    border-top-right-radius: 100px;
    border-bottom-left-radius: 40px;
    border-bottom-right-radius: 40px;
    position:relative;
    top:33px;
  }
  .logo{
    width:30px;
    height:10px;
    background:#A64942;
  }
  .stick{
    width:30px;
    height:40px;
    background:#FE5F55;
    border-bottom-left-radius:10px;
    border-bottom-right-radius:10px;
    position:relative;
    bottom:33px;
  }
</style>
```


[#36](https://cssbattle.dev/play/36)
```html
<div class="wrapper">
  <div class="stick yellow"></div>
  <div class="stick green"></div>
  <div class="stick yellow"></div>
  <div class="stick green"></div>
  <div class="stick yellow"></div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:flex;
    justify-content:center;
    align-items:center;
  } 
  .stick{
    height:200px;
    width:50px;
    margin:12px;
  }
  .yellow{
    background:#F3AC3C;
    border-top-right-radius:100px;
    border-top-left-radius:100px;
    position:relative;
    top:50px;
  }
  .green{
    background:#998235;
    border-bottom-right-radius:100px;
    border-bottom-left-radius:100px;
    position:relative;
    bottom:50px;
  }
</style>
```

[#37](https://cssbattle.dev/play/37)
```html
<div class="wrapper">
  <div class="square1">
    <div class="square2">
      <div class="square3"></div>
    </div>
  </div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #6592CF;
    display:grid;
    place-items:center;
  }
  .square1{
    width:250px;
    height:250px;
    background:#243D83;
    display:grid;
    place-items:center;
  }
  .square2{
    width:150px;
    height:150px;
    background:#6592CF;
    display:grid;
    place-items:center;
    transform:rotate(15deg);
  }
  .square3{
     width:75px;
    height:75px;
    background:#243D83;
    transform:rotate(15deg);
  }
</style>
```

[#38](https://cssbattle.dev/play/38)
```html
<div class="wrapper">
  <div class="container">
    <div class="square1"></div>
    <div class="container-1">
      <div class="rectangle-1"></div>
      <div class="rectangle-2"></div>
    </div>
  </div> 
  <div class="container">
    <div class="rectangle-3"></div>
    <div class="rectangle-4"></div>
  </div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #293462;
    display:flex;
  }
  .square1{
    width: 200px;
    height: 200px;
    background: #FFF1C1;
  }
  .container{
    width:200px;
    height:300px;
  }
  .container-1{
    width:200px;
    height:100px;
    display:flex;
  }
  .rectangle-1{
    width:150px;
    height:100px;
    background:#FE5F55
  }
  .rectangle-2{
    width:50px;
    height:100px;
    background:#A64942;
  }
 .rectangle-3{
    width:100px;
    height:150px;
    background:#FE5F55
  }
 .rectangle-4{
    width:100px;
    height:50px;
    background:#A64942;
 }
</style>
```

[#39](https://cssbattle.dev/play/39)
```html
<div class="wrapper">
  <div class="circle">
  </div>
  <div class="rectangle"></div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:grid;
    place-items:center;
  }
  .circle{
    width:200px;
    height:200px;
    border-radius:50%;
    background:#998235;
    display:flex;
    justify-content:center;
    align-items:center;
    position:relative;
    top:50px;
  }
  .rectangle{
    width:250px;
    height:140px;
    border-radius:50px;
    position:relative;
    bottom:120px;
    background:linear-gradient(#1A4341 14.28%, #F3AC3C 14.28% 28.56%, #1A4341 28.56% 42.84%, #F3AC3C 42.84% 57.12%, #1A4341 57.12% 71.4%, #F3AC3C 71.4% 85.63%, #1A4341 85.63%);
  }
</style>
```html


[#40](https://cssbattle.dev/play/40)
```html
<div class="wrapper">
  <div class="container">
    <div class="circle">
      <div class="inner-circle"></div>
    </div>
    <div class="square"></div>
  </div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #6592CF;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .container{
    position:relative;
    left:50px;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .circle{
    width:200px;
    height:200px;
    background:#243D83;
    border-radius:50%;
    display:grid;
    place-items:center;
  }
  .inner-circle{
    width:100px;
    height:100px;
    background:#6592CF;
    border-radius:50%;
  }
  .square{
    position:relative;
    bottom:50px;
    right:200px;
    width:100px;
    height:100px;
    background:linear-gradient(to right,#243D83 50%, #6592CF 50%);
  }
</style>
```html


[#41](https://cssbattle.dev/play/41)
```html
<div class="wrapper">
  <div class="top">
    <div class="head">
      <div class="eye"></div>
    </div>
    <div class="head rotate">
      <div class="eye rotate-eye"></div>
    </div>
  </div>
  <div class="bottom">
    <div class="sector"></div>
    <div class="sector rotate-sector"></div>
  </div>
</div>
<style>
  body{
    margin:0px;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #293462;
    display:grid;
    place-items:center;
  }
  .top{
    display:flex;
    justify-content:center;
    align-items:center;
    position:relative;
    top:35px;
  }
  .bottom{
    display:flex;
    justify-content:center;
    align-items:center;
    height:50px;
    width:100px;
    background:#FE5F55;
    position:relative;
    bottom:40px;
  }
  .head{
    height:100px;
    width:100px;
    background:linear-gradient( to right,#293462 50%, #FE5F55 50%);
    display:flex;
    justify-content:center;
    align-items:center;
    border-top-right-radius:40px;
  }
  .eye{
    height:30px;
    width:30px;
    border-radius:50%;
    background:#293462;
    position:relative;
    top:30px;
    left:30px;
  }
  .rotate{
   background:linear-gradient( to right, #FE5F55 50%,#293462 50%);
    border-top-left-radius:40px;
  }
  .rotate-eye{
    position:relative;
    bottom:30px;
    left:-30px;
  }
  .sector{
    height:50px;
    width:50px;
    border-top-right-radius:50px;
    background:#293462;
  }
  .rotate-sector{
    border-top-right-radius:0px;
    border-top-left-radius:50px;
  }
</style>
```html


[#42](https://cssbattle.dev/play/42)
```html
```html


[#43](https://cssbattle.dev/play/43)
```html
```html


[#44](https://cssbattle.dev/play/44)
```html
```html

[#45](https://cssbattle.dev/play/45)
```html
```html


[#46](https://cssbattle.dev/play/46)
```html
```html


[#47](https://cssbattle.dev/play/47)
```html
```html


[#48](https://cssbattle.dev/play/48)
```html
```html


[#49](https://cssbattle.dev/play/49)
```html
```html


[#50](https://cssbattle.dev/play/50)
```html
```html


[#51](https://cssbattle.dev/play/51)
```html
```html


[#52](https://cssbattle.dev/play/52)
```html
```html


[#53](https://cssbattle.dev/play/53)
```html
```html


[#54](https://cssbattle.dev/play/54)
```html
```html


[#55](https://cssbattle.dev/play/55)
```html
```html


[#56](https://cssbattle.dev/play/56)
```html
```html


[#57](https://cssbattle.dev/play/57)
```html
```html


[#58](https://cssbattle.dev/play/58)
```html
```html


[#59](https://cssbattle.dev/play/59)
```html
```html


[#60](https://cssbattle.dev/play/60)
```html
```html
