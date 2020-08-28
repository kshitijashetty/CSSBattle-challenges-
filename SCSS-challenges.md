# Yo bro! Wassup...
<p align="center">
  <img width="400px" height="400px" src="/images/Man.PNG">
</p>
Code snippet
```html
<div class="wrapper">
  <div class="wrapper__man">
    <div class="wrapper__man__head"></div>
    <div class="wrapper__man__body"></div>
    <div class="wrapper__man__hand-left"></div>
    <div class="wrapper__man__hand-right"></div>
    <div class="wrapper__man__leg wrapper__man__leg--left"></div>
    <div class="wrapper__man__leg wrapper__man__leg--right"></div>
  </div>
</div>
<style>
body{
  margin:0;
}
.wrapper {
  width: 400px;
  height: 400px;
  background: purple;
  display: flex;
  align-items: center;
  justify-content: center;
  &__man {
    width: 100px;
    height: 250px;
    display: grid;
    place-items: center;
    &__head {
      width: 50px;
      height: 50px;
      background: white;
      border-radius: 50%;
      position: relative;
      top: -10px;
    }
    &__body {
      width: 60px;
      height: 100px;
      background: white;
    }
    &__leg {
      width: 28px;
      height: 100px;
      border-bottom-left-radius: 20px;
      border-bottom-right-radius: 20px;
      background: white;
      position: relative;
      &--left {
        left: -16px;
        top: -140px;
      }
      &--right {
        right: -16px;
        top: -240px;
      }
    }

    &__hand-left {
      width: 20px;
      height: 80px;
      background: white;
      border-radius: 0px 10px;
      transform: rotate(25deg);
      position: relative;
      left: -40px;
      top: -100px;
    }
    &__hand-right {
      border-right: 20px white solid;
      border-bottom: 20px white solid;
      border-radius: 15px;
      width: 60px;
      height: 40px;
      position: relative;
      right: -40px;
      bottom: 220px;
      animation: wave 3s infinite;
      animation-delay:0s;
      @keyframes wave {
        0%, 20%{
          transform:skew(-15deg);
        }
        20%, 40%{
          transform:skew(15deg);
        }
        40%, 60% {
          transform:skew(-15deg);
        }
        60%, 80% {
          transform:skew(15deg);
        }
        80%, 100% {
          transform:skew(-15deg);
        }
     }
    }
  }
}
</style>
```
