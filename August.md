[#1](https://cssbattle.dev/play/1)
```html
<div class="wrapper">
  <div class="square"></div>
</div>
<style>
 .wrapper
{
  position:absolute;
  top:0px;
  left:0px;
  width:400px;
  height:300px;
  background: #5d3a3a;
}
  .square{
    height:200px;
    width:200px;
    background:#b5e0ba;
  }
</style>
```

[#2](https://cssbattle.dev/play/2)
```html
<div class="wrapper">
  <div class="container">
    <div class="sec">
      <div class="square"></div>
    </div>
    <div class="sec">
      <div class="square"></div>
    </div>
  </div>
  <div class="container">
    <div class="sec">
      <div class="square"></div>
    </div>
    <div class="sec">
      <div class="square"></div>
    </div>
  </div>
</div>
<style>
  .wrapper {
  position:absolute;
  top:0px;
  left:0px;
  width: 400px;
  height: 300px;
  display: grid;
  place-items: center;
  background: black;
}
.container{
  width: 400px;
  height: 150px;
  display:flex;
  align-items: center;
  justify-content: center;
}
.sec {
  width: 100%;
  height: 100%;
  background: #62374e;
  display: flex;
  align-items: center;
  justify-content: center;
}
.square {
  height: 50px;
  width: 50px;
  background: #fdc57b;
}
</style>
```

[#3](https://cssbattle.dev/play/3)
```html
<div id="wrapper">
  <div id="container">
      <div id="circle1">
        <div id="circle2">
          <div id="circle3"></div>
        </div>
      </div>
  </div>
</div>

<style>
  #circle1{
  display: grid;
  place-items:center;
  height:250px;
  width:250px;
  border-radius:50%;
  background:#6592CF;
  position:relative;
}
#circle2{
  display: grid;
  place-items:center;
  height:150px;
  width:150px;
  border-radius:50%;
  background:#243D83;
  position:relative;
}
#circle3{
  height:50px;
  width:50px;
  border-radius:50%;
  background:#EEB850;
  position:relative;
}
#container{
  background: linear-gradient(#6592CF 20%, #243D83 20% 80%,   #6592CF 80%);
  width: 300px;
  height: 250px;
  display: grid;
  place-items:center;
  position:relative;
}
#wrapper{
  
  position:absolute;
  top:0px;
  left:0px;
  display: grid;
  place-items:center;
  background: #6592CF;
  width: 400px;
  height: 300px;
}
</style>
```

[#4](https://cssbattle.dev/play/4)
```html
<div id="wrapper">
  <div id="container">
    <div id="shape2">    
    </div>
    <div id="shape1">
    </div>
    <div id="shape2">
    </div>
  </div>
</div>
<style>
  #wrapper{
  position:absolute;
  top:0px;
  left:0px;
  background:#62306D;
  height: 300px;
  width:400px;
  display:grid;
  place-items:center;
}
#container{
  background:#62306D;
  height: 200px;
  width:350px;
  display:flex;
  justify-content:center;
  justify-items:center;
}
#shape1{
  height:100px;
  width:100px;
  border-top-left-radius:50%;
  border-top-right-radius:50%;
  background:#F7EC7D;
}
#shape2{
  height:100px;
  width:100px;
  top:100px;
  border-bottom-left-radius:50%;
  border-bottom-right-radius:50%;
  background:#F7EC7D;
  position:relative;
}
</style>
```

[#5](https://cssbattle.dev/play/5)
```html
<div class="wrapper">
  <div class="circle1"></div>
  <div class="circle2"></div>
  <div class="circle3"></div>
</div>
<style>
  .wrapper
{
  position:absolute;
  top:0px;
  left:0px;
  width:400px;
  height:300px;
  background: #0B2429;
  display:grid;
  align-content:center;
  justify-content:center;
}
.circle1{
  position:relative;
  top:50%;
  background: #F3AC3C;
  width:120px;
  height:120px;
  border-radius:50%;
  left:50%;
}
.circle2{
  position:relative;
  background: #998235;
  width:120px;
  height:120px;
  border-radius:50% 1% 50% 50%;
}
.circle3{
  right:50%;
  top:-50%;
  position:relative;
  background: #F3AC3C;
  width:120px;
  height:120px;
  border-radius:50% 1% 50% 50%;
}
</style>
```

[#6](https://cssbattle.dev/play/6)
```html
<div class="div">
  <div class="part1"></div>
  <div class="part2"></div>
</div>
<style>
  .div {
    position: absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #E3516E;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .part1{
    width:100px;
    height:200px;
    border-bottom-left-radius: 200px;
    border-top-left-radius: 200px;
    background:linear-gradient(#51B5A9 50%, #F7F3D7 50%)

  }
  .part2{
    width:100px;
    height:200px;
    border-bottom-right-radius: 200px;
    border-top-right-radius: 200px;  
    background:linear-gradient(#FADE8B 50%, #E3516E 50%)
  }
  
</style>
```

[#7](https://cssbattle.dev/play/7)
```html
<div class="div">
	<div class="leaf1"></div>
    <div class="leaf2"></div>
    <div class="leaf3"></div>  
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #0B2429;
    display:flex;
    justify-content:center;
    align-content:center;
    align-items:center;
  }
  .leaf1{
    height:160px;
    width:160px;
    background:#1A4341;
    border-radius:60% 0%;
    position:relative;
    left:55px;
  }
  .leaf2{
    height:160px;
    width:160px;
    background:#998235;
    border-radius:60% 0%;
    position:relative;
    right:30px
  }
  .leaf3{
    height:160px;
    width:160px;
    background:#F3AC3C;
    border-radius:60% 0%;
    position:relative;
    right:110px;
  }
</style>
```

[#8](https://cssbattle.dev/play/8)
```html
<div class="div">
  <div class="container">
  	<div class="shape3"></div>
    <div class="shape4"></div>
    <div class="shape3"></div>
    <div class="shape4"></div>
    <div class="shape3"></div>
    <div class="shape4"></div>
    <div class="shape3"></div>
  </div>
  <div class="shape1"></div>
  <div class="shape2"></div>
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px; 
    width: 400px;
    height: 300px;
    background: #6592CF;
    display: grid;
    place-items:center;
  }
  .container{
    display: flex;
  }
  .shape3{
    width:20px;
    height:110px;
    background:#060F55;
    bottom:-30%;
    position:relative;
    border-top-left-radius:100px;
    border-top-right-radius:100px;
  }
  .shape4{
    width:20px;
    height:110px;
    background:#6592CF;
    bottom:-40%;
    position:relative;
    z-index:1;
    border-bottom-left-radius:100px;
    border-bottom-right-radius:100px;
  }
  .shape1{
    width:140px;
    height:110px;
    background:#060F55;
    bottom:-30%;
    position:relative;
    border-bottom-left-radius:100px;
    border-bottom-right-radius:100px;
  }
  .shape2{
    width:20px;
    height:100px;
    background:#060F55;
  }
</style>
```

[#9](https://cssbattle.dev/play/9)
```html
<div class="wrapper">
  <div class="outer-square">
    <div class="inner-square">
      <div class="circle"></div>
    </div>
  </div>
</div>
<style>
  body{
    margin:0px;
  }
 .wrapper{
    width: 400px;
    height: 300px;
    background: linear-gradient(#222730 25%, #4CAAB3 25% 75%, #222730 75%);
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .outer-square{
     background:#222730;
     width:250px;
     height:250px;
     transform:rotate(45deg);
     display:flex;
     align-items:center;
     justify-content:center;
  }
  .inner-square{
     background:#4CAAB3;
     width:150px;
     height:150px;
     display:grid;
     place-items:center;
  }
  .circle{
    background:#393E46;
    width:50px;
    height:50px;
    border-radius:50%;
  }
</style>
```

[#10](https://cssbattle.dev/play/10)
```html
<div class="clocked">
  <div class="clocked__spirit-small">
    <div class="clocked__spirit-small--circle1 small--color1">
      <div class="clocked__spirit-small--circle2 small--color2"></div>
    </div>
    <div class="clocked__spirit-small--square1"></div>
  </div>
  <div class="clocked__spirit-big">
    <div class="clocked__spirit-small--circle1 big--color1">
      <div class="clocked__spirit-small--circle2 big--color2"></div>
    </div>
    <div class="clocked__spirit-big--square2"></div>
  </div>
  <div class="clocked__spirit-small">
    <div class="clocked__spirit-small--circle1 small--color1">
      <div class="clocked__spirit-small--circle2 small--color2"></div>
    </div>
    <div class="clocked__spirit-small--square3"></div>
  </div>
</div>
<style>
.clocked {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #62306D;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .clocked__spirit-small{
    height:100px;
    width:100px;
    background:linear-gradient(#62306D 50%, #F7EC7D 50%);
    position:relative;
    bottom:-16.5%;
  }
  .clocked__spirit-big{
    height:250px;
    width:100px;
    background:linear-gradient(#62306D 19%, #F7EC7D 19%);
    position:relative;
    bottom:-8.5%;
  }
  .clocked__spirit-small--square1{
    height:50px;
    width:100px;
    position: relative;
    background:#F7EC7D;
  }
  .clocked__spirit-big--square2{
    height:100px;
    width:100px;
    background:#F7EC7D;
    position: relative;
  }
  .clocked__spirit-small--square3{
    height:50px;
    width:100px;
    background:#F7EC7D;
    position: relative;
  }
.clocked__spirit-small--circle1{
    height:100px;
    width:100px;
    border-radius: 50%;
    display:grid;
    place-items:center;
}
.clocked__spirit-small--circle2{
    height:60px;
    width:60px;
    border-radius: 50%;
}
.big--color1{
  background: #E38F66;
}
.big--color2{
  background:#AA445F;
}

.small--color1{
  background:#AA445F;
}

.small--color2{
  background:#E38F66;
}
</style>
```

[#11](https://cssbattle.dev/play/11)
```html
<div class="div">
  <div class="sc1">
    <div class="sc11"></div>
  </div>
  <div class="c1">
    <div class="cc1">
      <div class="cc2"></div>
    </div>
  </div>
  <div class="sc2">
    <div class="sc22"/></div>
  </div>
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #191210;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .sc1{
    width:100px;
    height:100px;
    position:relative;
    left:5%;
    background:linear-gradient(#191210 50%, #ECA03D 50%);
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .c1{
    width:140px;
    height:140px;
    background:#ECA03D;
    border-radius:50%;
    z-index:1;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .cc1{
    width:100px;
    height:100px;
    background:#191210;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .cc2{
    width:50px;
    height:50px;
    background:#84271C;
    border-radius:50%;
  }
  .sc2{
    width:100px;
    height:100px;
    background:#ECA03D;
    border-radius:50%;
    position:relative;
    right:5%;
    background:linear-gradient(#ECA03D 50%, #191210 50%);
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .sc11{
    width:60px;
    height:60px;
    background:#191210;
    border-radius:50%;
  }
  .sc22{
    width:60px;
    height:60px;
    background:#191210;
    border-radius:50%;
  }
</style>
```

[#12](https://cssbattle.dev/play/12)
```html
<div class="wrapper">
  <div class="curvedown c1">
    <div class="circle"></div>
  </div>
  <div class="curveup">
  	<div class="circle"></div>
  </div>
  <div class="curvedown c2">
    <div class="circle"></div>
  </div>
</div>
<style>
  .wrapper {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #F5D6B4;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .curveup{
    background:linear-gradient(#D86F45 50%,#F5D6B4 50%);
    //border:20px #D86F45 solid;
    height:100px;
    width:100px;
    border-radius:50%;
    display:grid;
    place-items:center;
  }
  .curvedown{
    position:relative;
    background:linear-gradient(#F5D6B4 50%, #D86F45 50%);
    //border:20px #D86F45 solid;
    border-radius:50%;
    width:100px;
    height:100px;
    display:grid;
    place-items:center;
  }
  .circle{
    background:#F5D6B4;
    border-radius:50%;
    width:60px;
    height:60px;
  }
  .c1{
    left:5%;
  }
  .c2{
    right:5%;
  }
</style>
```

[#13](https://cssbattle.dev/play/13)
```html
<div class="div">
  <div class="top"></div>
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #0B2429;
  }
  .top{
    position:relative;
    width:140px;
    height:140px;
    background:linear-gradient(-45deg, #0B2429 50%, #F3AC3C 50%);
  }
</style>
```

[#14](https://cssbattle.dev/play/14)
```html
<div class="div">
  <div class="triangle2 overlap1 color3"></div>
  <div class="triangle2 color4"></div>
  <div class="triangle1 color1"></div>
  <div class="triangle1 overlap2 color2"></div>
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #F2F2B6;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .triangle1{
    z-index:1;
    width: 0;
	height: 0;
	border-left: 80px solid transparent;
	border-right: 80px solid transparent;
  }
 .triangle2{
    width: 0;
	height: 0;
	border-left: 80px solid transparent;
	border-right: 80px solid transparent;
  }
  .overlap1{
    position:relative;
    left:190px;
  }
  .overlap2{
    position:relative;
    right:190px;
  }
  .color1{
    border-bottom: 120px solid #FF6D00;
  }
  .color2{
    border-bottom: 120px solid #FD4602;
  }
  .color3{
    border-top: 120px solid #FD4602;
  }
  .color4{
    z-index:1;
    border-top: 120px solid #FF6D00;
  }
</style>
```

[#15](https://cssbattle.dev/play/15)
```html
<div class="div">
  <div class="c1"></div>
  <div class="c3"></div>
  <div class="c2"></div>
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #09042A;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .c1{
    border-radius:50%;
    height:150px;
    width: 150px;
    background:#7B3F61;
    position:relative;
    left:15%;
  }
  .c2{
    border-radius:50%;
    height:150px;
    width:150px;
    background:#E78481;
    position:relative;
    right:10%;
  }
  .c3{
    z-index:1;
    height:115px;
    width:50px;
    background:#09042A;
    border-radius:50%;
    position:relative;
    left:2%;
  }
</style>
```

[#16](https://cssbattle.dev/play/16)
```html
<div class="div">
    <div class="eye">
      <div class="c1">
        <div class="c2">
          <div class="c3">
          </div>
        </div>
      </div>
    </div>
</div>
<style>
  .div {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #0B2429;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .eye{
    width:200px;
    height:200px;
    transform:rotate(45deg);
    background-color:#998235;
    border-radius:50% 0%;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .c1{
    width:180px;
    height:180px;
    background-color:#0B2429;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .c2{
    width:140px;
    height:140px;
    background-color:#F3AC3C;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .c3{
    width:50px;
    height:50px;
    background-color:#0B2429;
    border-radius:50%;
  }

</style>
```

[#17](https://cssbattle.dev/play/17)
```html

```


[#18](https://cssbattle.dev/play/18)
```html
<div class="wrapper">
  <div class="column">
    <div class="s1"></div>
    <div class="s2 top"></div>
    <div class="s1 top3"></div>
  </div>
  <div class="column">
    <div class="s2"></div>
    <div class="s1 top"></div>
    <div class="s2 top3"></div>
  </div>
  <div class="column">
    <div class="s1"></div>
    <div class="s2 top"></div>
    <div class="s1 top3"></div>
  </div>
  <div class="column">
    <div class="s2"></div>
    <div class="s1 top"></div>
    <div class="s2 top3"></div>
  </div>
</div>
<style>
   .wrapper {
    position:absolute;
    top:0px;
    left:0px;
    width: 400px;
    height: 300px;
    background: #5C434C;
    display:flex;
  }
 .s1{
    height:80px;
    width:80px;
    position:relative;
    margin:10px 0px 0px 10px;
    border-radius:100% 0 0 0;
    background:#F09462;
  }
.s2{
    height:80px;
    width:80px;
    position:relative;
    margin:10px 0px 0px 10px;
    border-radius:100% 0 0 0;
    background:#F5D6B4;
  }
.column{
  height:300px;
  width:100px;
}
.top{
  position:relative;
  top:10px;
}
.top3{
  position:relative;
  top:20px;
}

</style>
```

[#19](https://cssbattle.dev/play/19)
```html
<div class="div">
  <div class="container">
 	 <div class="square pos1"></div>
  </div>
  <div class="square pos2"></div>
</div>
<style>
  .div {
    width: 400px;
    height: 300px;
    background: #0B2429;
    position:absolute;
    top:0px;
    left:0px;
    display:grid;
    place-items:center;
  }
  .container{
    width:140px;
    height:140px;
    background:red;
    display:flex;
    align-items:center;
    justify-content:center;
    position:relative;
    top:30px;
    background:linear-gradient(#0B2429 50%, #998235 50%);
  }
  .square{
    width:100px;
    height:100px;
    transform:rotate(45deg);
    position:relative;
  }
  .pos1{
    background:linear-gradient(45deg, #998235 50%, #1A4341 50%);
  }
  .pos2{
    bottom:50px;
    background:#F3AC3C;
  }
</style>
```

[#20](https://cssbattle.dev/play/20)
```html
<div class="div">
  <div class="part1">
    <div class="sec-big TL"></div>
    <div class="sec-big BL"></div>
    <div class="sec-small TR-1"></div>
    <div class="sec-small BR-1"></div>
  </div>
  <div class="part2">
    <div class="sec-small TL"></div>
    <div class="sec-small BL"></div>
    <div class="sec-big TR"></div>
    <div class="sec-big BR"></div>
  </div>
  
</div>
<style>
  body{
    margin:0px;
  }
  .div {
    width: 400px;
    height: 300px;
    background: #62306D;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .part1{
    width: 140px;
    height: 100px;
    background: #F7EC7D;
  }
  .part2{
    width: 60px;
    height: 100px;
    background: #E38F66;
  }
  .sec-big{
    width:20px;
    height:20px;
    background:#62306D;
  }
  .sec-small{
    width:10px;
    height:10px;
    background:#62306D;
  }
  .BL{
    border-radius:0 100% 0 0; 
    position:absolute;
    bottom:100px
  }
  .TL{
    border-radius:0 0 100% 0;
  }
  .BR{
    border-radius:100% 0 0 0;
    position:absolute;
    right:100px;
    bottom:100px
  }
  .TR{
    border-radius:0 0 0 100%; 
    position:absolute;
    top:100px;
    right:100px;
  }
  .BR-1{
    border-radius:100% 0 0 0;
    position:absolute;
    right:160px;
    bottom:100px
  }
  .TR-1{
    border-radius:0 0 0 100%; 
    position:absolute;
    top:100px;
    right:160px;
  } 
</style>
]
```

[#21](https://cssbattle.dev/play/21)
```html

```

[#22](https://cssbattle.dev/play/22)
```html

```

[#23](https://cssbattle.dev/play/23)
```html

```

[#24](https://cssbattle.dev/play/24)
```html

```

[#25](https://cssbattle.dev/play/25)
```html

```

[#26](https://cssbattle.dev/play/26)
```html

```

[#27](https://cssbattle.dev/play/28)
```html

```

[#28](https://cssbattle.dev/play/28)
```html

```
