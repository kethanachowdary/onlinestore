<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Online-Store</title>
    <style>
      * {
        margin: 0px;
      }

      .container {
        background-color: white;
      }
      .header {
        display: flex;
        justify-content: space-between;
        background-color: orange;
      }
      .row {
        display:flex;
        justify-content: center;
        background-color: silver;

      }
      .row1 {
        display: flex;
        justify-content: center;
        background-color: white;
      }
      .row2 {
        display: flex;
        justify-content: center;
        background-color: silver;
      }
      .box {
        background-color: whitesmoke;
        margin: 20px;
        padding: 10px;
      }
      li {
        display:inline-block;
        padding: 10px;
        font-size: larger;
      }
      a{
        text-decoration: none;
      }
      a:hover {
        text-decoration: underline;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="header">
        <div><h1>Online Store</h1></div>
        <div>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Service</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="login.html">Login</a></li>
            <li><a href="signup.html">Signup</a></li>
          </ul>
        </div>
      </div>
      <div class="row">
        <div class="box">
          <img src="C:\Users\GRIET\Desktop\onlinestore\assets\images\1.png" />
          <h2>Product 1</h2>
          <p>This is the description of the product.</p>
          <h3>Rs 230</h3>
          <button>Add to Cart</button>
        </div>
        <div class="box">
          <img src="C:\Users\GRIET\Desktop\onlinestore\assets\images\2.png" />
          <h2>Product 2</h2>
          <p>This is the description of the product.</p>
          <h3>Rs 200</h3>
          <button>Add to Cart</button>
        </div>
        <div class="box">
          <img src="C:\Users\GRIET\Desktop\onlinestore\assets\images\3.png" />
          <h2>Product 3</h2>
          <p>This is the description of the product.</p>
          <h3>Rs 375</h3>
          <button>Add to Cart</button>
        </div>
      </div>
      <div class="row1">
        <div class="box">
          <img src="C:\Users\GRIET\Desktop\onlinestore\assets\images\4.jpg"/>

          
        </div>
        <div class="box">
            <h2>Product 4</h2>
          <p>This is the description of the product</p>
          <h3>Rs 290</h3>
          <button>Add to Cart</button>

        </div>
      </div>
      <div class="row2">
        <div class="box">
            <h2>Product 5</h2>
          <p>This is the description of the product</p>
          <h3>Rs 300</h3>
          <button>Add to Cart</button>

        </div>
        <div class="box">
            <img src="C:\Users\GRIET\Desktop\onlinestore\assets\images\6.jpg"/>
          
                
          </div>
        

        </div>
      </div> 
            
      
    </div>
  </body>
</html>


signup



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
        margin: 0px;
      }
        .box {
  background-color: rgb(127, 127, 237);
  justify-content: center;
  display:flex;
  text-align: center;
  
  
  margin: 20px;
  padding: 10px;
  
}
.header {
        display: flex;
        justify-content: flex;
        background-color: orange;
      }
</style>
</head>
<body>
    <div class="header">
        <div><h1>Signup</h1></div>
    </div>
<div class="box">
    <form>

   
    
  <label>Name</label>
  <input type="text">
  <br><br>
  <label>Mobile Number</label>
  <input type="text">
  <br><br>
  <label>Email id</label>
  <input type="text">
  <br><br>
  <label>Password</label>
  <input type="text">
  <br><br>
  <label>Confirm Password</label>
  <input type="text">
  <br><br>
  <label>Address</label>
  <input type="text">
  <br><br>

  

  <button>SUBMIT</button>
  </form>

</div>
    
</body>
</html>




login




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
        margin: 0px;
      }
              .box {
        background-color: rgb(127, 127, 237);
        justify-content: center;
        display:flex;
        text-align: center;
        
        margin: 20px;
        padding: 10px;
        
      }
      .header {
        display: flex;
        justify-content: flex;
        background-color: orange;
      }
    </style>
</head>
<body>
    <div class="header">
        <div><h1>Login</h1></div>
    </div>
    <div class="box">
        
        <form>
            <label>Username</label>
        <input type="text">
        <br><br>
        <label>Password</label>
        <input type="text">
        <br><br>
        

        <button>enter</button>
        </form>

        

    </div>
    
</body>
</html>
