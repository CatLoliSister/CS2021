# htmla.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>Tis is 4100E115-廖柏洋 speaking</title>
	<meta charset="utf-8">
<style>
ul {
  color: #000000;
}

ol {
  color: #000000;
}

p {
  text-align: center;
  color: green;
}
 
.nocenter{
  color: #000000;
}

.center{
  text-align: center;
  color: #9AFF02;
}

body{
margin:0px;
padding:0px;
background:#fff url(86-eighty-six.gif) center center fixed no-repeat;
background-size: cover;　
}       

.oneblock{
  text-align: center;
  color: #FF5809;
}
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: #9F4D95;
  background-color: transparent;
  text-decoration: none;
}

a:active {
  color: #4F9D9D;
  background-color: transparent;
  text-decoration: none;
}
</style>
</head>

<body>

<h1 class="oneblock">網頁建置程式設計</h1>

<h3 class="oneblock">4100E115 廖柏洋 Liao Bo-Yang</h3>

<h3 class="oneblock"><a href="https://github.com/CatLoliSister/CS2021" target="_blank">Gifhub</a></h3>

<h3 class="oneblock">指導老師:偉大的恩師 曾龍</h3>
<hr/>

<h2 class="center">清單 分兩種</h2>

<hr/>

<h3 class="nocenter">html標籤 => u1</h3>

<ul>
  <li>AAA</li>
  <li>BBB</li>
  <li>CCC</li>
</ul>  

<h3 class="nocenter">html標籤 => o1</h3>

<ol>
  <li>111</li>
  <li>222</li>
  <li>333</li>
</ol>


<input type="radio">




  <label for="domTextElement">Name: </label>
  <input type="text" id="domTextElement" > 
  
  <button type="button"  onclick="getValueInput()"> 
      click me!! 
  </button> 
  
  <p id="valueInput"></p> 

  <script> 

    const getValueInput = () =>{
      let inputValue = document.getElementById("domTextElement").value; 
      document.getElementById("valueInput").innerHTML = inputValue; 
    }
    
  </script> 




</body>
</html>
```
