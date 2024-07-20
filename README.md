# MD-store
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<link rel="stylesheet" href="style.css">
<style>
h3{color:white;}
img {
border: 1px solid #ddd;
border-radius: 4px;
padding: 5px;
width: 150px;
}
img:hover{
box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}
{
box-sizing: border-box;
}
.slider {
    position: relative;
    width: 80%;
    max-width: 600px;
    overflow: hidden;
    border: 2px solid #ccc;
    border-radius: 10px;
    background-color: #fff;
}
.slides {
    display: flex;
    transition: transform 0.5s ease-in-out;
}
.slides img {
    width: 100%;
    border-right: 2px solid #ccc;
}
button {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    border: none;
    color: white;
    padding: 10px;
    cursor: pointer;
    border-radius: 50%;
}
button.prev {
    left: 10px;
}
button.next {
    right: 10px;
}
button:hover {
background-color: rgba(0, 0, 0, 0.8);
}
.topnav{
overflow: hidden;
background-color:#333;
}
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
.header{
background-color:white;
padding: 20px;
text-align:center;
}
table, th, td {
border: 2px solid black;
border-collapse: collapse;
}
</style>
<tital title="MD STORE"><small>MD Store</small></tital>
<hr>
</head>
<body style="background-color:gray;">
<div class="header">
<h1>Md Store</h1>
</div>
<div class="topnav">
<a href="#HOODIEZ">HOODIEZ</a>
<a href="#BLOOVERS">BLOOVERS</a>
<a href="#"></a>
<a href="#"></a>
</div>
<div class="slider">
<div class="slides">
<img src="Pic/IMG_E8478.JPG" alt="Image 1">
<img src="Pic/IMG_E8483.JPG" alt="Image 2">
</div>
<button class="prev">&#10094;</button>
<button class="next">&#10095;</button>
</div>
<hr>
<hr>
<h3 id="HOODIEZ">HOODIEZ<h3>
<a target="_blank" href="Pic/IMG_E6258.JPG">
<img src="Pic/IMG_E6258.JPG" alt="Hoodie" style="width:150px">
</a>
<h2 style="color:white">Price:16.000KD</h2>
<form><label for="Quantity">Quantity</label><input type="number" id="Quantity" name="quantity" min="1" max="10" value="1"></form>
<p style="color:white"><ins>Choose Size</ins></p>
<form action="/action_page.php">
<input type="radio" id="S" name="Size" value="S">
<label for="S">S</label><br>
<input type="radio" id="S" name="Size" value="M">
<label for="M">M</label><br>
<input type="radio" id="L" name="Size" value="L">
<label for="L">L</label><br>
<input type="radio" id="XL" name="Size" value="XL">
<label for="XL">XL</label><br><br>
<input type="submit" value="Submit">
</form>
<hr>
<a target="_blank" href="Pic/IMG_E6255.JPG">
<img src="Pic/IMG_E6255.JPG" alt="Hoodie" style="width:150px">
</a>
<h2 style="color:white">Price:16.000KD</h2>
<form><label for="Quantity">Quantity</label><input type="number" id="Quantity" name="quantity" min="1" max="10" value="1"></form>
<p style="color:white"><ins>Choose Size</ins></p>
<form action="/action_page.php">
<input type="radio" id="S" name="Size" value="S">
<label for="S">S</label><br>
<input type="radio" id="S" name="Size" value="M">
<label for="M">M</label><br>
<input type="radio" id="L" name="Size" value="L">
<label for="L">L</label><br>
<input type="radio" id="XL" name="Size" value="XL">
<label for="XL">XL</label><br><br>
<input type="submit" value="Submit">
</form>
<hr>
<h3 id="BLOOVERS">BLOOVERS<h3>
<a target="_blank" href="Pic/IMG_E8484.JPG">
<img src="Pic/IMG_E8484.JPG" alt="Hoodie" style="width:150px">
</a>
<h2 style="color:white">Price:15.000KD</h2>
<form><label for="Quantity">Quantity</label><input type="number" id="Quantity" name="quantity" min="1" max="10" value="1"></form>
<p style="color:white"><ins>Choose Size</ins></p>
<form action="/action_page.php">
<input type="radio" id="S" name="Size" value="S">
<label for="S">S</label><br>
<input type="radio" id="S" name="Size" value="M">
<label for="M">M</label><br>
<input type="radio" id="L" name="Size" value="L">
<label for="L">L</label><br>
<input type="radio" id="XL" name="Size" value="XL">
<label for="XL">XL</label><br><br>
<input type="submit" value="Submit">
</form>
<hr>
<table style="width:40%">
<tr>
<th>Avaliable Sizes</th>
</tr>
<tr>
<td>S</td>
</tr>
<tr>
<td>M</td>
</tr>
<tr>
<td>L</td>
</tr>
<tr>
<td>XL</td>
</tr>
</table><br>
<a title="MD SHOPQ8 INSTAGRAM"href="https://www.instagram.com/md.shopq8?"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/800px-Instagram_logo_2022.svg.png"style="width:30px;height:30px;"</a>
<imag src="IMG_E6256.JPG"alt="Md sss"style="wedth:200px;height:200px">
<script src="script.js"></script>
<script>
const slides = document.querySelector('.slides');
const images = document.querySelectorAll('.slides img');
let currentIndex = 0;
document.querySelector('.next').addEventListener('click', () => {
currentIndex++;
if (currentIndex >= images.length) {
currentIndex = 0;
}
updateSlidePosition();
});
document.querySelector('.prev').addEventListener('click', () => {
currentIndex--;
if (currentIndex < 0) {
currentIndex = images.length - 1;
}
updateSlidePosition();
});
function updateSlidePosition() {
slides.style.transform = `translateX(${-currentIndex * 100}%)`;
}
</script>
</body>
</html>
