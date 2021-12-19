# Company-website-bootstrap

## AIM
create a company website using bootstrap components

# ALGORITHM
### STEP 1
create a simple html page using heading tag
### STEP 2
Add a Bootstrap cdn link to access bootstrap components
### STEP 3
Use bootstrap components to build a website
### STEP 4
Execute the program

# CODE
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Website Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
      *{
          color: black;
      }
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>

<div class="jumbotron text-center" style="margin-bottom:0">
  <h1>AIO allinone</h1>
</div>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">AIO</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li class="active"><a href="#">Products</a></li>
        <li class="active"><a href="#">About Us</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container">
  <div class="row">
   
    <div class="col-sm-8">
      <h2>TITLE HEADING</h2>
      <div class="fakeimg">Fake Image</div>
      <p>Some text..</p>
      <br>
      <h2>TITLE HEADING</h2>
      <h5>Title description, Sep 2, 2017</h5>
      <div class="fakeimg">Fake Image</div>
      <p>Some text..</p>
    </div>
  </div>
</div>

<div class="jumbotron text-center" style="margin-bottom:0">
  <p>Footer</p>
</div>

</body>
</html>
~~~
# OUPUT
![SEC](exp7.png)
![SEC](exp7_2.png)

# RESULT
company website using bootstrap components was successfully executed.