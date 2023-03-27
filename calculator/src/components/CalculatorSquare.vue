<template>
<div class="calculator">
<div class="input"> </div>
<div class="calc div2">C/CE</div>
<div class="calc div3">+/-</div>
<div class="calc div4">√</div>
<div class="calc div5">%</div>
<div class="calc div6">MRC</div>
<div class="calc div7">M-</div>
<div class="calc div8">M+</div>
<div class="calc div9">÷</div>
<div class="calc div10">7</div>
<div class="calc div11">8</div>
<div class="calc div12">9</div>
<div class="calc div13">×</div>
<div class="calc div14">4</div>
<div class="calc div15">5</div>
<div class="calc div16">6</div>
<div class="calc div17">-</div>
<div class="calc div18">1</div>
<div class="calc div19">2</div>
<div class="calc div20">3</div>
<div class="calc div21">0</div>
<div class="calc div22">.</div>
<div class="calc div23">=</div>
<div class="calc div24">+</div>
</div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Lilita+One&display=swap');

.calculator {
  border: 3px solid black;
color: white;
font-family: 'Lilita One', cursive;
border-radius: 1%;
width: 550px;
height: 750px;
display: grid;
background-color: rgb(75, 75, 75);
grid-template-columns: repeat(4, 1fr);
grid-template-rows: repeat(7, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
}
.calc {
  border: 3px solid black;
  font-size: 40px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: rgb(20, 20, 20);
  cursor: pointer;
  margin: 10px;
  border-radius: 10px;
}
.input {
  border: 3px solid black;
background-color: rgb(20, 20, 20);
grid-area: 1 / 1 / 2 / 5;
height: 125px;
margin: 20px 10px 10px 10px;
border-radius: 10px;
}


.div2 { grid-area: 2 / 1 / 3 / 2; }
.div3 { grid-area: 2 / 2 / 3 / 3; }
.div4 { grid-area: 2 / 3 / 3 / 4; }
.div5 { grid-area: 2 / 4 / 3 / 5; }
.div6 { grid-area: 3 / 1 / 4 / 2; }
.div7 { grid-area: 3 / 2 / 4 / 3; }
.div8 { grid-area: 3 / 3 / 4 / 4; }
.div9 { grid-area: 3 / 4 / 4 / 5;
font-size: 60px; }
.div10 { grid-area: 4 / 1 / 5 / 2; }
.div11 { grid-area: 4 / 2 / 5 / 3; }
.div12 { grid-area: 4 / 3 / 5 / 4; }
.div13 { grid-area: 4 / 4 / 5 / 5;
  font-size: 60px; }
.div14 { grid-area: 5 / 1 / 6 / 2; }
.div15 { grid-area: 5 / 2 / 6 / 3; }
.div16 { grid-area: 5 / 3 / 6 / 4; }
.div17 { grid-area: 5 / 4 / 6 / 5;
  font-size: 60px; }
.div18 { grid-area: 6 / 1 / 7 / 2; }
.div19 { grid-area: 6 / 2 / 7 / 3; }
.div20 { grid-area: 6 / 3 / 7 / 4; }
.div21 { grid-area: 7 / 1 / 8 / 2; }
.div22 { grid-area: 7 / 2 / 8 / 3; }
.div23 { grid-area: 7 / 3 / 8 / 4; }
.div24 { grid-area: 6 / 4 / 8 / 5;
  font-size: 60px; }
</style>