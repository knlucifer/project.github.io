<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  
<style >
  
.fa {
  padding: 20px;
  font-size: 30px;
  width: 70px;
  text-align: center;
  text-decoration: none;
  margin: 2px 55px;
  border-radius: 50%;
}
.fa-facebook {
  background: #3B5998;
  color: white;
}
.fa-google {
  background: #dd4b39;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}

</style>
</head>
<body>


<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">KnFavors</a>
    </div>
    <ul class="nav navbar-nav">
      <li ><a href="https://www.netflix.com">Home</a></li>
      <li><a href="aboutus.html">about us</a></li>
      <li><a href="service.html">Services</a></li>
    </ul>
    <form class="navbar-form navbar-left" action="/action_page.php">
      <div class="input-group">
        <input type="text" class="form-control" placeholder="Search" name="search">
        <div class="input-group-btn">
          <button class="btn btn-default" type="submit">
            <i class="glyphicon glyphicon-search"></i>
          </button>
        </div>
      </div>
    </form>
     <ul class="nav navbar-nav navbar-right">
      <li><a href="#"data-toggle="modal" data-target="#myModal"><span class="glyphicon glyphicon-user"></span> Sign Up</a></li>
      <li><a href="index1.html"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
    </ul>
  </div>
</nav>

<!--slide starts here-->
<div class="container-fluid">

  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      <div class="item active">
        <img src="got.jpg" alt="Los Angeles" style="width:100%;">
      </div>

      <div class="item">
        <img src="luci.jpg" alt="Chicago" style="width:100%;">
      </div>

      <div class="item">
        <img src="st.jpg" alt="New york" style="width:100%;">
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<!--slide ends here-->

	<h1 class="jumbotron text-center">Mapping</h1>
 <!--map starts here-->
 <div>
 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3549.4005538501765!2d78.0399535150506!3d27.175144783015206!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39747121d702ff6d%3A0xdd2ae4803f767dde!2sTaj%20Mahal!5e0!3m2!1sen!2sin!4v1605887031166!5m2!1sen!2sin" width="1400" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
</div>
 <!--map ends here-->

 <!--model starts here-->
 <div class="container">


  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog" >
    <div class="modal-dialog modal-dialog-centered" >

      <!-- Modal content-->
      <div class="modal-content" >
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4 class="modal-title">Sign up</h4>
        </div>
        <div class="modal-body">
          <div class="form-group" >
   <label for="usr">Username:</label>
    <input type="text" class="form-control" placeholder="Enter Username" id="usr">
   
  </div>
  <div class="form-group">
  <label for="pwd">Password:</label>
  <input type="password" class="form-control" placeholder="Enter password" id="pwd">
     </div>

  <div class="form-group">
   <label for="pwd">Repeat Password:</label>
   <input type="Repeat password" class="form-control" placeholder="Enter password" id="pwd">
  </div>
    <div class="form-group">
  <label for="pwd">Email</label>
  <input type="Email ID" class="form-control" placeholder="Enter Email" id="pwd">
      </div>
       <div class="form-group">
  
      <input type="submit"value="create account" class="btn btn-success btn-block"/></br>
        <center>
          <h4>Or</h4>
        </center>  
        <a href="https://www.facebook.com" class="fa fa-facebook"></a>
        <a href="https://www.google.com" class="fa fa-google"></a>     
         <a href="https://www.twitter.com" class="fa fa-twitter"></a>             
      </div>
        </div>
      </div>
    </div>
  </div>
</div>
<!--model ends here-->
</body>
</html>
