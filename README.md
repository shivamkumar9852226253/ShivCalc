# ShivCalc
<html> 
 <head> 
  <meta charset="utf-8"> 
  <title>  
         &lt;h1&gt; &lt;b&gt;&lt;em&gt; SHIVAMCALC&lt;/em&gt;&lt;/b&gt;&lt;/h1&gt; 
    </title> 
  <link href="https://fonts.googleapis.com/css2?family=Cookie&amp;display=swap" rel="stylesheet"> <!-- CSS property to create interactive  
        calculator interface --> 
  <style>  
body    
{    
background-color: tan;    
}    
.box    
{    
background-color: #3d4543;    
height: 300px;    
width: 270px;    
border-radius: 10px;    
position: relative;    
top: 80px;    
left: 40%;    
}   
.display    
{    
background-color: #222;    
width: 220px;    
position: relative;    
left: 15px;    
top: 20px;    
height: 40px;    
}    
.display input    
{    
position: relative;    
left: 2px;    
top: 2px;    
height: 35px;    
color: black;    
background-color: #bccd95;    
font-size: 21px;    
text-align: right;    
}   
.keys    
{    
position: relative;    
top: 15px;    
}    
.button    
{    
width: 40px;    
height: 30px;    
border: none;    
border-radius: 8px;    
margin-left: 17px;    
cursor: pointer;    
border-top: 2px solid transparent;    
}    
.button.gray    
{    
color: black;  
font-color: black;    
background-color: #6f6f6f;    
border-bottom: black 2px solid;    
border-top: 2px #6f6f6f solid;    
}  
.title:hover {  
   color: #fff;  
}  
.title {  
margin-bottom: 10px;  
margin-top: 30px;  
padding: 5px 0;  
font-size: 40px;  
font-weight: bold;  
text-align: center;  
color: black;  
font-family: 'Cookie', cursive;  
}  
    
.button.pink    
{    
color: black;    
background-color: #ff4561;    
border-bottom: black 2px solid;    
}    
.button.black    
{    
color: black;    
background-color: 303030;    
border-bottom: black 2px solid;    
border-top: 2px 303030 solid;    
font-weight: bold;  
}    
.button.orange    
{    
color: black;    
background-color: FF9933;    
border-bottom: black 2px solid;    
border-top: 2px FF9933 solid;    
}    
.gray:active    
{    
border-top: black 2px solid;    
border-bottom: 2px #6f6f6f solid;    
}    
.pink:active    
{    
border-top:black 2px solid;    
border-bottom:#ff4561 2px solid;    
}    
.black:active    
{    
border-top: black 2px solid;    
border-bottom: #303030 2px solid;    
}    
.orange:active    
{    
border-top: black 2px solid;    
border-bottom: FF9933 2px solid;    
}    
p    
{    
line-height: 10px;    
}   
</style> 
 </head> 
 <body> 
  <div class="title? align=" centre"> 
   <center> 
    <h1><b><em>SHIVAM CALC</em></b></h1> 
   </center> 
  </div> 
  <div class="box"> 
   <div class="display"> 
    <input type="text" readonly size="18" id="d"> 
   </div> 
   <div class="keys"> 
    <p> <input type="button" class="button gray" value="mrc" onclick="c(&quot;Created...........by.........&quot;)"> <input type="button" class="button gray" value="m-" onclick="c(&quot;Shivam Kumar Thakur&quot;)"> <input type="button" class="button gray" value="m+" onclick="c(&quot;ShivamKumar9852226253@gmail.com&quot;)"> <input type="button" class="button blue" value="/" onclick="v(&quot;/&quot;)"> </p> 
    <p> <input type="button" class="button black" value="7" onclick="v(&quot;7&quot;)"> <input type="button" class="button black" value="8" onclick="v(&quot;8&quot;)"> <input type="button" class="button black" value="9" onclick="v(&quot;9&quot;)"> <input type="button" class="button blue" value="*" onclick="v(&quot;*&quot;)"> </p> 
    <p> <input type="button" class="button black" value="4" onclick="v(&quot;4&quot;)"> <input type="button" class="button black" value="5" onclick="v(&quot;5&quot;)"> <input type="button" class="button black" value="6" onclick="v(&quot;6&quot;)"> <input type="button" class="button blue" value="-" onclick="v(&quot;-&quot;)"> </p> 
    <p> <input type="button" class="button black" value="1" onclick="v(&quot;1&quot;)"> <input type="button" class="button black" value="2" onclick="v(&quot;2&quot;)"> <input type="button" class="button green" value="3" onclick="v(&quot;3&quot;)"> <input type="button" class="button green" value="+" onclick="v(&quot;+&quot;)"> </p> 
    <p> <input type="button" class="button black" value="0" onclick="v(&quot;0&quot;)"> <input type="button" class="button black" value="." onclick="v(&quot;.&quot;)"> <input type="button" class="button black" value="C" onclick="c(&quot;&quot;)"> <input type="button" class="button orange" value="=" onclick="e()"> </p> 
   </div> 
  </div> 
  <script>  
function c(val)    
{    
document.getElementById("d").value=val;    
}    
function v(val)    
{document.getElementById("d").value+=val;    
}    
function e()    
{    
try    
    {    
     c(eval(document.getElementById("d").value))    
    }    
    catch(e)    
    {    
     c('Error') }    
}  
</script> 
 </body>
</html>
