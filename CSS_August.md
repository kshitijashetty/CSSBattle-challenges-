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
```


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
```


[#42](https://cssbattle.dev/play/42)
```html
<!--Not very accurate -->
<div class="wrapper">
  <div class="container">
    <div class="face">
      <div class="hair left"></div>
      <div class="hair right"></div>
    </div>
    <div class="con">
      <div class="eye"></div>
      <div class="eye"></div>
    </div>
    <div class="mouth"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #293462;
    display:grid;
    place-items:center;
  }
  .container{
    display:grid;
    place-items:center;
    position:relative;
    top:50px;
    //background:red;
  }
  .face{
    width:200px;
    height:200px;
    display:flex;
    border-top-left-radius:100px;
    border-top-right-radius:100px;
    border-bottom-right-radius:50px;
    border-bottom-left-radius:50px;
    background:#FE5F55;
  }
  .con{
    display:flex;
  }
  .eye{
    width:60px;
    height:60px;
    background:#FFF1C1;
    border-radius:50%;
    margin:20px;
    position:relative;
    bottom:130px;
  }
  .hair{
    height:80px;
    width:80px;
    background:linear-gradient(#293462 58%,#FFF1C1 58%);
    border-bottom-left-radius:50%;
    border-bottom-right-radius:50%;
    position:relative;
    /*height:80px;
    width:40px;
    border-top-left-radius:50px;
    border-top-right-radius:40px;
    border-bottom-left-radius:50px;
    border-bottom-right-radius:40px;
    background:red;*/
    
  }
  .left{
    transform:rotate(-30deg);
    left:20px;
    top:-35px;
  }
  .right{
    transform:rotate(30deg);
    left:20px;
    top:-35px;
  }
  .mouth{
    height:10px;
    width:40px;
    border-radius:20px;
    background:#FFF1C1;
    position:relative;
    bottom:130px;
  }
</style>
```


[#43](https://cssbattle.dev/play/43)
```html
<div class="wrapper">
  <div class="part one">
    <div class="inner"></div>
  </div>
  <div class="part two">
  	<div class="inner"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #6592CF;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .part{
    background:#243D83;
    height:240px;
    width:110px;
    border-radius:40px;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .inner{
    background:#6592CF;
    height:180px;
    width:80px;
    border-radius:40px;
  }
  .one{
    background:linear-gradient(to right, #6592CF 50%,#243D83 50%);
  }
  .two{
    background:linear-gradient(to right,#243D83 50%, #6592CF 50%);
  }
</style>
```


[#44](https://cssbattle.dev/play/44)
```html
<div class="wrapper">
  <div class="semi left"></div>
  <div class="rectangle"></div>    
  <div class="semi right"></div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .semi{
    height: 270px;
    width: 115px;
    background: #1A4341;
  }
  .left{
    position:relative;
    right:-20px;
    border-bottom-right-radius: 270px;
    border-top-right-radius: 270px;
  }
  .right{
    position:relative;
    left:-20px;
    border-bottom-left-radius: 270px;
    border-top-left-radius: 270px;
  }
  .rectangle{
    width:160px;
    height:180px;
    background:linear-gradient(#F3AC3C 11%, #1A4341 11% 22%, #F3AC3C 22% 33%, #1A4341 33% 44%, #F3AC3C 44% 55%, #1A4341 55% 66%,#F3AC3C 66% 77%, #1A4341 77% 88%, #F3AC3C 88%);
  }
</style>
```

[#45](https://cssbattle.dev/play/45)
```html
<div class="wrapper">
    <div class="square-1">
      <div class="square-2">
        <div class="partition"></div>
      </div>
    </div>
  <div class="line"></div>
  
</div>
<style>
  body{
    margin:0;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:grid;
    justify-content:center;
  }
  .square-1{
    width:210px;
    height:180px;
    border:30px solid #F3AC3C ;
    border-top:0px;
    display:flex;
    justify-content:center;
  }
  .square-2{
    width:90px;
    height:120px;;
    border:30px solid #998235 ;
    border-top:0px;
  }
  .line{
    width:270px;
    height:10px;
    border-top:30px solid #998235;
    position:relative;
    top:5px;
  }
  .partition{
    z-index:1;
    height:300px;
    width:30px;
    background:#F3AC3C;
    position:relative;
    right:-30px;
  }
</style>
```


[#46](https://cssbattle.dev/play/46)
```html
```


[#47](https://cssbattle.dev/play/47)
```html
<div class="wrapper">
  <div class="container">
    <div class="line one"></div>
    <div class="line two"></div>
    <div class="line three"></div>
    <div class="circle">
      <div class="circle-1"></div>
      <div class="circle-2"></div>
      <div class="circle-3"></div>
    </div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper{
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .container{
    display:grid;
    place-items:center;
    transform:rotate(-180deg);
    position:relative;
    bottom:50px;
  }
  .line{
    height:180px;
    width:10px;
    border-radius:10px;
    background:#F3AC3C;
  }
  .one{
    position:relative;
    top:190px;
  }
  .two{
    transform:rotate(60deg);
    position:relative;
  }
  .three{
    transform:rotate(-60deg);
    position:relative;
    bottom:200px;
  }
  .circle{
    height:100px;
    width:100px;
    border-radius:50%;
    background:#F3AC3C;
    position:relative;
    bottom:320px;
  }
  .circle-1{
    height:10px;
    width:10px;
    border-radius:50%;
    background:#998235;
    position:relative;
    top:70px;
    left:20px;
  }
   .circle-2{
    height:30px;
    width:30px;
    border-radius:50%;
    background:#998235;
    position:relative;
    top:40px;
    left:50px;
  }
   .circle-3{
    height:20px;
    width:20px;
    border-radius:50%;
    background:#998235;
    position:relative;
    top:-25px;
    left:40px;
  }
</style>
```


[#48](https://cssbattle.dev/play/48)
```html
<div class="wrapper">
  <div class="box shadow"></div>
  <div class="box">
    <div class="box-inner"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper{
    width: 400px;
    height: 300px;
    background: #293462;
    display:grid;
    place-items:center;
  }
  .box{
    height:100px;
    width:200px;
    background:#FE5F55;
    border-radius:20px;
    display:grid;
    place-items:50%;  
    position:relative;
    bottom:85px;
    display:grid;
    place-items:center;
  }
  .shadow{
    height:100px;
    width:200px;
    background:#A64942;
    position:relative;
    top:85px;
  }
  .box-inner{
    width:140px;
    height:40px;
    border-radius:75px;
    background:#A64942;
  }
</style>
```


[#49](https://cssbattle.dev/play/49)
```html
<div class="wrapper">
  <div class="triangle"></div>
  <div class="rectangle">
    <div class="window"></div>
    <div class="door"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper{
    width: 400px;
    height: 300px;
    background: #6592CF;
    display:grid;
    place-items:center;
  }
  .triangle{
    width:0px;
    height:0px;
    position:relative;
    top:25px;
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
   border-bottom: 100px solid #243D83;
}
  .rectangle{
    height:100px;
    width:150px;
    background:#243D83;
    position:relative;
    bottom:25px;
    display:grid;
    place-items:center;
    border-bottom-left-radius:10px;
    border-bottom-right-radius:10px;
  }
  .window{
    width:100px;
    height:10px;
    border-radius:50px;
    background:#EEB850;
    position:relative;
    bottom:15px;
  }
  .door{
    position:relative;
    top:10px;
    width:50px;
    height:50px;
    background:#EEB850;
    border-top-left-radius:10px;
    border-top-right-radius:10px;
  }
</style>
```


[#50](https://cssbattle.dev/play/50)
```html
<div class="wrapper">
  <div class="handle"></div>
  <div class="handle-1"></div>
  <div class="drop"></div>
  <div class="drop"></div>
  <div class="neck-1"></div>
  <div class="neck-2"></div>
  <div class="body">
    <div class="wave one"></div>
    <div class="wave two"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper{
    width: 400px;
    height: 300px;
    background: #1A4341;
    display:grid;
    place-items:center;
  }
  .handle{
    position:relative;
    top:50px;
    left:20px;
    width:160px;
    height:20px;
    background:#F3AC3C;
    border-radius:10px;
  }
  .handle-1{
    position:relative;
    left:90px;
    top:40px;
    width:20px;
    height:30px;
    background:#F3AC3C;
    border-bottom-left-radius:10px;
    border-bottom-right-radius:10px;
  }
  .neck-1{
    position:relative;
    bottom:45px;
    width:20px;
    height:25px;
    background:#F3AC3C;
  }
  .neck-2{
    position:relative;
    bottom:48px;
    width:50px;
    height:20px;
    background:#F3AC3C;
    border-top-left-radius:10px;
    border-top-right-radius:10px;
  }
  .drop{
    position:relative;
    left:90px;
    top:50px;
    width:20px;
    height:20px;
    border-radius:50%;
    background:#998235;
    margin:5px;
  }
  .wave{
    height:50px;
    width:50px;
    border-radius:50%;
    position:relative;
    bottom:10px;
  }
  .one{
    background:#998235;
  }
  .two{
    background:#F3AC3C;
  }
  .body{
    position:relative;
    bottom:50px;
    width:100px;
    height:140px;
    border-radius:20px;
    background:linear-gradient(#F3AC3C 45%, #998235 45%);
    display:flex;
    justify-content:center;
    align-items:center;
  }
</style>
```


[#51](https://cssbattle.dev/play/51)
```html
<div class="wrapper">
  <div class="handle">
    <div class="child"></div>
  </div>
  <div class="mask">
    <div class="bar"></div>
    <div class="bar"></div>
    <div class="circle"></div>
  </div>
  <div class="handle right">
    <div class="child"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper{
    width: 400px;
    height: 300px;
    background: #293462;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .handle{
    position:relative;
    top:-20px;
    width:60px;
    height:60px;
    border-top-left-radius:50px;
    border-bottom-left-radius:50px;
    background:#FFF1C1;
    display:grid;
    place-items:center;
  }
  .child{
    width:40px;
    height:40px;
    border-top-left-radius:25px;
    border-bottom-left-radius:25px;
    background:#293462;
  }
  .right{
    transform:rotate(-180deg);
  }
  .mask{
    width:150px;
    height:100px;
    border-bottom-left-radius:50px;
    border-bottom-right-radius:50px;
    background:#FFF1C1;
  }
  .bar{
    height:10px;
    width:40px;
    background:#FE5F55;
    margin:10px;
    border-radius:10px;
    position:relative;
    top:10px;
    left:10px;
  }
  .circle{
    height:40px;
    width:40px;
    border-radius:50%;
    background:#FE5F55;  
    position:relative;
    top:-10px;
    left:90px;
  }
</style>
```


[#52](https://cssbattle.dev/play/52)
```html
<div class="wrapper">
  <div class="container one">
    <div class="circle-1"></div>
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
  <div class="container two">
    <div class="circle-2"></div>
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
  <div class="container three">
    <div class="circle-1"></div>
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
  <div class="container four">
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
  <div class="container five">
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
  <div class="container six">
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
  <div class="container seven">
    <div class="circle"></div>
    <div class="chain"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper{
    width: 400px;
    height: 300px;
    background: #6592CF;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .container{
    display:flex;
    align-items:center;
    justify-content:center;
    margin:10px;
    position:relative;
  }
  .chain{
    height:47px;
    width:10px;
    background:#243D83;
    position:relative;
    left:15px;
    top:16px;
  }
  .circle{
    position:relative;
    left:30px;
    top:-10px;
    height:20px;
    width:20px;
    border-radius:50%;
    background:#243D83;
  }
  .circle-1{
    position:relative;
    left:60px;
    top:-10px;
    background:#EEB850;
    height:40px;
    width:40px;
    border-radius:50%;
  }
  .circle-2{
    position:relative;
    left:70px;
    top:-20px;
    background:#EEB850;
    height:60px;
    width:60px;
    border-radius:50%;
  }
  .one{
    left:5px;
  }
  .two{
    left:-60px;
  }
  .three{
    left:-105px;
  }
  .four{
    left:-80px;
  }
  .five{
    left:-85px;
  }
  .six{
    left:-90px;
  }
  .seven{
    left:-95px;    
  }
</style>
```


[#53](https://cssbattle.dev/play/53)
```html
<div class="wrapper">
  <div class="rectangle"></div>
  <div class="circle">
    <div class="sector"></div>
  </div>
</div>
<style>
  body{
    margin:0;
  }
  .wrapper {
    width: 400px;
    height: 300px;
    background: #19191A;
    display:grid;
  }
  .rectangle{
    position:relative;
    left:130px;
    top:125px;
    height:125px;
    width:75px;
    background:#F9E492;
  }
  .circle{
    height:150px;
    width:150px;
    border-radius:50%;
    background:#4F77FF;
    position:relative;
    left:130px;
    top:-88px;
  }
  .sector{
    position:relative;
    top:75px;
    height:75px;
    width:75px;
    border-radius: 0 0 0 100%;
    background:#9AD5FF;
  }
</style>

```


[#54](https://cssbattle.dev/play/54)
```html
```


[#55](https://cssbattle.dev/play/55)
```html
```


[#56](https://cssbattle.dev/play/56)
```html
```


[#57](https://cssbattle.dev/play/57)
```html
```


[#58](https://cssbattle.dev/play/58)
```html
```


[#59](https://cssbattle.dev/play/59)
```html
```


[#60](https://cssbattle.dev/play/60)
```html
```
