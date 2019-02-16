# efremovavm-2.github.io<!DOCTYPE html>
<html>

  <head>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
    <style>
    BODY {
  align-items: center;
  justify-content: center;
  background: white;
  font-family: Georgia;
  }

H1 {
  font-size: 30px;
  font-weight: normal;
  cursor: pointer;
  text-shadow: 0 0 15px #999;
  color: transparent;
  transition: all .5s;
  }
  H1:hover {
    text-shadow: 0 0 0px #333;
    cursor: pointer;
    }
  {
   </style>
 <script> 
 function func1(){ 
 var a;
 a=Number(document.getElementById("a_znach").value);
 document.getElementById("kont_a").innerHTML ="<h1>"+"Периметр"+"<br>"+ a*4+"</h1>";
 }
 
 function func2(){
var r;
 r=Number(document.getElementById("b_znach").value);
 document.getElementById("b").innerHTML ="<h1>"+"Диаметр"+"<br>"+ r*2+"</h1>";
 }
 function func3(){
var ab;
 ab=Number(document.getElementById("g").value);
 var b = ab%10;
 document.getElementById("qwe").innerHTML ="<h1>"+"единиц"+"<br>"+ b+"</h1>";
 }
 
 </script>
 </head>
 <body>
  <h1>Задача 1.25</h1>
  Сторона квадрата a=<input type="text" value="0" id="a_znach">
  <button onclick="func1()">1.25</button>
  <div id="kont_a"></div>
  <h1>Задача 1.26</h1>
  Радиус r=<input type="text" value="0" id="b_znach">
  <button onclick="func2()">1.26</button>
  <div id="b"></div>
  
   <h1>Задача 2.10</h1>
   f=<input type="text" value="23" id="g">
  <button onclick="func3()">2.10</button>
  <div id="qwe"></div>
    
  </body> 
 </html>
 
