<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Meeting Henny</title>
</head>
<style>
    * {
        box-sizing: border-box;
        padding: 0;
        margin: 0;
    }
    img{
        float: right;
        border-radius: 300px;
        width: 50%;
    }
    ul{
        list-style-type: disc;
    }
    ol.R{
        list-style-type; lower-greek;
    }
    body{
        font-family: cursive;
        background: tomato;
        margin-bottom: 500px;
    }
    .note{
        font-family: Trebuchet MS;
        font-size: 70px;
        color:red;
    }
    .div__city {
        column-count: 3;
        overflow-x: visible;
        
    }
    .city{
        color: white;
        margin: auto;
        padding: ;
        
    }
    table {
        font-family: Courier New,arial,sans-serif;
        border-collapse: collapse;
        border-spacing: 40px;
        border-color: black;
        width:100%;
    }
    th, td{
        border: 20px solid #aaaaaa;
        text-align: center;
        vertical-align: middle;
        padding: 8px;
    }
    th{
        background: #11998e;
    }
    tr:nth-child(even) {background-color: #3c2c0f3d;}
    tr.hover:{
        background: #1b2e4156;
    }
    summary {
        font-family: Trubechet MS;
        outline: none;
    }
    .hamburger {
        float: right;
        clear: both;
        width: 50px;
        height: 50px;
        background: black;
        position: absolute;
        top: 0px;
        right: 0px;
        display: flex;
        flex-flow: column wrap;
        justify-content: space-evenly;
        align-content: space-evenly;
    }
    .line1 {
        background-color: white;
        width: 20px;
        height: 2px;
        position: relative;
        left: 15px;
        border-radius: 25%;
    }
    .line2 {
        background-color: white;
        width: 20px;
        height: 2px;
        position: relative;
        left: 15px;
        border-radius: 25%;
    }
    .line3 {
        background-color: white;
        width: 20px;
        height: 2px;
        position: relative;
        left: 15px;
        border-radius: 25%;
    }
    .menus{
        visibility: hidden;
        position: relative;
        top: 50px;
        right: 20px;
    }
    .hamburger:hover{
         display: flex;
        flex-flow: column wrap;
        justify-content: space-evenly;
        align-content: space-evenly;
    } 
    .hamburger:hover .menus {
       visibility: visible;
        z-index: 1;
    } 
    nav {
    flex-flow: column;
    display: flex;
    justify-content: center;
    position: sticky;
    top: 0;         
    background: gold;
    margin: auto;
  }
  nav a{
      display: block;
      justify-content: center;
      align-items: center;
      align-content: center;
      color: teal;
      width: 100%;
      text-decoration: none;
      flex-flow: row wrap;
      border-bottom: 1px solid white;
      border-height: 50px;
      padding: 10px;
  }
  nav a:last-child {
      border-bottom: none;
  }
  
  nav a:hover {
  color: white;
  transition: color 1s;
</style>
<body style=" margin: 10px;">
    
    <h2><strong>CHAPTER 1</strong></h2>
        <div class="hamburger">
            <div class="line1"></div>
            <div class="line2"></div>
            <div class="line3"></div>
            <div class="menus">
                <nav>
                <a href="project.html">Home</a>
                <a href="second semester results.html">About</a>
                <a href="signup-project.html">Contact us</a>
                </nav>
            </div>
        </div>
    
    <h1>Henny</h1>
    <h2>Henny</h2>
    <h3>Henny</h3>
    <h4>Henny</h4>
    <h5>Henny</h5>
    <h6>Henny</h6>
    
    <img src="./Henny.jpg" alt="Henny's picture">
    <p>My name is <strong>Abdulazeez Mueez Eniola</strong>.<b> I am a student of LASUSTECH.</b> Department of <em> computer engineering</em></p>
    <p></p>
              <strong>List</strong>
    <ul>
        <li>Megan</li>
        <li>mission impossible</li>
        <li>Colombiana</li>
    </ul>
    <ol>
        <li> its okay to not be okay</li>
        <li> squid game</li>
        <ul>
            <li>season 1</li>
            <ol class="R">
                <li>Green light red light</li>
                <li>Dalogna</li>
            </ol>
            <li>season 2</li>
            <li>season 3</li>
        </ul>
        <li> Dear Hongrang</li>
    </ol>
    <div class="groupone">
        <h2>Action movies</h2>
        <p>I also love Korean Drama</p>
    </div>
        <h2>Eating</h2>
        <p>Rice is my favorite food</p>
        
   <a href="https://www.facebook.com">Facebook</a>
    <br>
    <a href="form basics.html">Basic forms</a>
    
    <footer><h2><strong>CHAPTER 2</strong></h2></footer>
    
    <table id="comparison">
        <thead>
            <th>phone</th>
            <th>Name</th>
            <th>Rating</th>
        </thead>
        
        <tr>
           <td>Tecno</td>
           <td>pop 10</td>
           <td>7</td>
        </tr>
          
        <tr>
            <td>itel</td>
            <td>A80</td>
            <td>6</td>
        </tr>
        
        <tr>
           <td>iphone</td>
           <td>16 pro max</td>
           <td>7</td>
        </tr>
        
        <tr>
           <td>Samsung</td>
           <td>s 25</td>
           <td>7</td>
        </tr>
    </table>    
    
    <div class="div__city">
        <div class="city">
            <h3>HTML</h3>
            <p>This is referred to as the framework of a piece of writing.</p>
        </div>
        
        <div class="city">
            <h3>CSS</h3>
            <p>This is known as the design and decoration of a piece of writing.</p>
        </div>
        
        <div class="city">
            <h3>JavaScript</h3>
            <p>This is the moving element of a piece of writing.</p>
        </div>
     </div>  
        <h3> <span class="note">ordinary differential equation</span></h3>
      
        
    </table>
           <h4>comments</h4>
           <!-- comments never get displayed -->
           <input type="text" style="margin-bottom: 20px;">
<figure>
    <img src="whitecat.png" width="300px" alt="cat image.">
    <figuration>Fig.1 - White cat</figuration>
</figure>
<details style="margin:8px; border: none;">
    <summary>Click to find out more about henny.</summary>
    <p style="20px">Ops! you really wanna know more. I really don't have anything to say.</p>
</details>
<meter value="15" min="0" max="30"></meter>
<form action="/submit_form" method="post">
  <label for="username">Username:</label><br>
  <input type="text" id="username" name="username" placeholder="Enter your username"><br><br>
  <input type="submit" value="Submit">
</form>
https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg
<main>
  <h1>CatPhotoApp</h1>
  <h2>Cat Photos</h2>
  <!-- TODO: Add link to cat photos -->
  <p>Everyone loves cute cats online!</p>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg">
</main>
<!-- <!DOCTYPE html>
<html>
  <body>
    <main>
      <h1>CatPhotoApp</h1>
      <h2>Cat Photos</h2>
       TODO: Add link to cat photos
      <p>Everyone loves cute cats online!</p>
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A relaxing cat">
    </main>
  </body>
</html> 
-->
<script> 
    var x = 2
    if(x > 10) {
    document.write ("value of x is greater than 10");
}
else {
  document.write ("value of x is equal 20");
}

for (a = 10;a >= 20;a++)
{
    document.write (a + "<br/>")
}
</script>
</body>
</html>
