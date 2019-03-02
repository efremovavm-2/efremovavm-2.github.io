<!DOCTYPE html>
<html>

  <head>
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

  function func9(){
var a;
 a=Number(document.getElementById("4la").value);
 b=(a-(a-a%100)-a%10)/10;
 document.getElementById("4l").innerHTML = "<h1>"+"число десятков"+"<br>"+ b +"</h1>";
  a=Number(document.getElementById("4la").value);
   document.getElementById("4l").innerHTML = document.getElementById("4l").innerHTML+ "<h1>"+"сумма цифр"+"<br>" +"</h1>";
    a=Number(document.getElementById("4la").value);
 b=(a-(a-a%100)-a%10)/10;
 c=(a-a%100)/100;
 m=b*a%10*c;
 document.getElementById("4l").innerHTML = document.getElementById("4l").innerHTML+ "<h1>"+"произведение чисел"+"<br>" +"</h1>";
   
   
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
  <h1>Задача 2.12</h1>
  трехзначное число=<input type="text" value="123" id="4la">
  <button onclick="func9()">2.12</button>
  <div id="4l"></div>
  <h1>Задача 1.26</h1>
  Радиус r=<input type="text" value="0" id="b_znach">
  <button onclick="func9()">2.12</button>
  <div id="b"></div>
  
  </body>

</html>
 
