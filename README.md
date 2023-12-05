*,
*:before,
*:after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  background-color: #fff2c8;
}
.container {
  width: 380px;
  height: 500px;
  position: absolute;
  transform: translate(-50%, -50%);
  top: 50%;
  left: 50%;
}
.container *:before,
.container *:after {
  position: absolute;
  content: "";
}
.santa {
  height: 220px;
  width: 200px;
  background-color: #e84701;
  border-radius: 80px;
  position: absolute;
  left: 115px;
  top: 200px;
}
.santa:before,
.santa:after {
  width: 40px;
  margin: auto;
  left: 0;
  right: 0;
  background-color: #fff2c8;
}
.santa:before {
  height: 130px;
}
.santa:after {
  height: 40px;
  bottom: -15px;
}
.hand-l {
  background-color: #e84701;
  height: 90px;
  width: 105px;
  position: absolute;
  right: -30px;
  top: 20px;
  border-radius: 0 80px 0 0;
}
.hand-l:before {
  margin: auto;
  width: 35px;
  height: 15px;
  background-color: #ffffff;
  top: 85px;
  left: 71px;
}
.hand-l:after {
  height: 15px;
  width: 30px;
  background-color: #fad2af;
  left: 74px;
  top: 101px;
  border-radius: 0 0 30px 30px;
}
.hand-r {
  height: 150px;
  width: 180px;
  border: 30px solid transparent;
  border-bottom: 40px solid #e84701;
  position: absolute;
  left: -100px;
  bottom: 150px;
  border-radius: 50%;
  animation: wave 1.5s infinite;
  transform-origin: right;
}
@keyframes wave {
  50% {
    transform: rotate(15deg);
  }
}
.hand-r:before {
  width: 35px;
  height: 15px;
  background-color: #ffffff;
  transform: rotate(-50deg);
  top: 68px;
  left: -22px;
}
.hand-r:after {
  width: 30px;
  height: 15px;
  background-color: #fad2af;
  transform: rotate(-50deg);
  left: -31px;
  top: 58px;
  border-radius: 15px 15px 0 0;
}
.face {
  position: absolute;
  margin: auto;
  height: 180px;
  width: 180px;
  background-color: #fad2af;
  border: 25px solid #f2e6da;
  border-radius: 50%;
  left: 0;
  right: 0;
  bottom: 140px;
}
.beard {
  position: absolute;
  height: 90px;
  width: 180px;
  background-color: #ffffff;
  border-radius: 0 0 90px 90px;
  right: -25px;
  bottom: -25px;
}
.beard:before {
  width: 55px;
  height: 25px;
  background-color: #f2e6da;
  border-radius: 20px 0;
  left: 34px;
}
.beard:after {
  height: 25px;
  width: 55px;
  background-color: #f2e6da;
  border-radius: 0 20px;
  right: 34px;
}
.eyes {
  height: 12px;
  width: 12px;
  background-color: #0078ca;
  border-radius: 50%;
  position: absolute;
  top: 40px;
  left: 40px;
  box-shadow: 38px 0 #0078ca, 19px 20px #f69697;
}
.eyes:before {
  height: 12px;
  width: 25px;
  background-color: #ffffff;
  border-radius: 10px 0;
  left: -10px;
  bottom: 20px;
}
.eyes:after {
  height: 12px;
  width: 25px;
  background-color: #ffffff;
  border-radius: 0 10px;
  left: 32px;
  bottom: 20px;
}
.hat {
  position: absolute;
  height: 60px;
  width: 120px;
  background-color: #e84701;
  top: -98px;
  left: 85px;
  border-radius: 0 0 60px 60px;
}
.hat:before {
  height: 40px;
  width: 40px;
  background-color: #ffffff;
  left: 100px;
  top: -15px;
  border-radius: 50%;
}
.belt {
  position: absolute;
  width: 100%;
  height: 30px;
  background-color: #000000;
  top: 100px;
}
.belt:before {
  height: 100%;
  width: 40px;
  border: 7px solid #ffdc2e;
  margin: auto;
  left: 0;
  right: 0;
}
.belt:after {
  height: 5px;
  width: 15px;
  background-color: #ffdc2e;
  left: 100px;
  top: 12px;
}
.shoe {
  height: 20px;
  width: 20px;
  background-color: #000000;
  position: absolute;
  top: 220px;
  left: 60px;
  border-radius: 20px 0 0 0;
}
.shoe:before {
  height: 20px;
  width: 20px;
  background-color: #000000;
  top: 0;
  left: 60px;
  border-radius: 0 20px 0 0;
}
