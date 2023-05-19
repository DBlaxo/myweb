# myweb
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Theme Made By www.w3schools.com - No Copyright -->
  <title>Healty Lifestyle</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="css/mystyle.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>


</head>
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="50">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage">Habits</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#myPage">HOME</a></li>
        <li><a href="#band">OUR TEAM</a></li>
        <li><a href="#tour">PLAN</a></li>
        <li><a href="#contact">CONTACT</a></li>
        <li class="dropdown">
          <a class="dropdown-toggle" data-toggle="dropdown" href="#">MORE
          <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Merchandise</a></li>
            <li><a href="#">Extras</a></li>
            <li><a href="#">Media</a></li> 
          </ul>
        </li>
        <li><a href="#"><span class="glyphicon glyphicon-search"></span></a></li>
      </ul>
    </div>
  </div>
</nav>

<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="images/Split.webp" alt="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.healthline.com%2Fhealth%2Fhow-to-do-the-splits&psig=AOvVaw0xc98O65IK12Rwxn3XVwPp&ust=1667707701861000&source=images&cd=vfe&ved=0CA4QjhxqFwoTCKDigZGYlvsCFQAAAAAdAAAAABAD" width="1200" height="700">
        <div class="carousel-caption">
          <h3>Exercise</h3>
          <p>A habit that you should fall into</p>
        </div>      
      </div>

      <div class="item">
        <img src="images/healthyfood2.png" alt="https://i0.wp.com/mealplanningforbeginners.com/wp-content/uploads/2020/06/healthy-meal-plan.jpg?fit=999%2C667&ssl=1" width="1200" height="700">
        <div class="carousel-caption">
          <h3>Healthy Diet</h3>
          <p>What you eat is what you are</p>
        </div>      
      </div>
    
      <div class="item">
        <img src="images/lifeworkbalance.png" alt="Los Angeles" width="1200" height="700">
        <div class="carousel-caption">
          <h3>Life-Work Balance</h3>
          <p>Life is worth living</p>
        </div>      
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
</div>

<!-- Container (The Band Section) -->
<div id="band" class="container text-center">
  <h3>HABITS</h3>
  <p><em>We love life!</em></p>
  <p>Healthier habits may protect you from serious health problems like obesity and diabetes. New habits, like healthy eating and regular physical activity, may also help you manage your weight and have more energy. After a while, if you stick with these changes, they may become part of your daily routine. Old habits die hard. Changing your habits is a process that involves several stages. Sometimes it takes a while before changes become new habits. And, you may face roadblocks along the way. Are you thinking about being more active? Have you been trying to cut back on less healthy foods? Are you starting to eat better and move more but having a hard time sticking with these changes? It only takes one step to start the change, the first one. It is up to youx.</p>
  <br>
  <div class="row">
    <div class="col-sm-4">
      <p class="text-center"><strong>Dr. Mark McIntosh</strong></p><br>
      <a href="#demo" data-toggle="collapse">
        <img src="images/mark.jpeg" class="img-circle person" alt="Random Name" width="255" height="255">
      </a>
      <div id="demo" class="collapse">
        <p>Medical Consultant</p>
        <p>Loves Classical Music</p>
        <p>Habits Co-founder </p>
      </div>
    </div>
    <div class="col-sm-4">
      <p class="text-center"><strong>Ms Ilaria Sant</strong></p><br>
      <a href="#demo2" data-toggle="collapse">
        <img src="images/ilaria.jpg" class="img-circle person" alt="Random Name" width="255" height="255">
      </a>
      <div id="demo2" class="collapse">
        <p>Gym Leader</p>
        <p>Loves sports</p>
        <p>Team member since 2018</p>
      </div>
    </div>
    <div class="col-sm-4">
      <p class="text-center"><strong>Dr. Lisa Scott</strong></p><br>
      <a href="#demo3" data-toggle="collapse">
        <img src="images/lisa.webp" class="img-circle person" alt="Random Name" width="255" height="255">
      </a>
      <div id="demo3" class="collapse">
        <p>Family Therapist</p>
        <p>Loves country walks</p>
        <p>Habits Co-founder</p>
      </div>
    </div>
  </div>
</div>

<!-- Container (TOUR Section) -->
<div id="tour" class="bg-1">
  <div class="container">
    <h3 class="text-center">Plan Ahead</h3>
    <p class="text-center">Your career plays an important role in your life<br> Read through these plans and adopt the one that fits you!</p>
<!--    <ul class="list-group">
      <li class="list-group-item">September <span class="label label-danger">Sold Out!</span></li>
      <li class="list-group-item">October <span class="label label-danger">Sold Out!</span></li> 
      <li class="list-group-item">November <span class="badge">3</span></li> 
    </ul> -->
    
    <div class="row text-left">
      <div class="col-sm-4">
        <div class="thumbnail">
          
          <p><strong>Plan Active</strong></p>
          <p>Plan for those with high activity routine</p>
		  <ul>
		  <li>Upgrade your diet</li>
		  <li>Keep hydrated, 3.7 litres of water/day</li>
		  <li>Get enough rest</li>
		  <li>Doctor's visit</li>
		  <li>Monitor your coffee consumption</li>
		  </ul>
		  <br><br><br><br><br><br>
          <button class="btn" data-toggle="modal" data-target="#myModal">Get advice</button>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="thumbnail">
          
          <p><strong>Plan Medium Active</strong></p>
          <p>Plan for persons with medium activity routine</p>
		  <ul>
		  <li>Upgrade your diet, avoid eating out</li>
		  <li>Find your hotel's room when away</li>
		  <li>Unwind from the day's trouble</li>
		  <li>Limit the weight of the lugage</li>
		  
		  </ul>
		  <br><br><br><br><br><br><br>
          <button class="btn" data-toggle="modal" data-target="#myModal">Get advice</button>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="thumbnail">
          
          <p><strong>Plan Low Active</strong></p>
          <p>Plan for persons with low activity routine</p>
		  <ul>
		  <li>Walk to work, or a 20min walk before work</li>
		  <li>setting reminders to stand up every 30 minutes when working at a desk</li>
		  <li>taking the stairs instead of using the elevator</li>
		  <li>Monitor your coffee consumption</li>
		  <li>Avoid carbs in your diet</li>
		  </ul>
		  <br><br><br><br><br>
          <button class="btn" data-toggle="modal" data-target="#myModal">Get advice</button>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">
    
      <!-- Modal content-->
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">×</button>
          <h4><span class="glyphicon glyphicon-lock"></span> Place your order</h4>
        </div>
        <div class="modal-body">
          <form role="form">
            <div class="form-group">
              <label for="psw"><span class="glyphicon glyphicon-envelope"></span> Message</label>
              <input type="number" class="form-control" id="psw" placeholder="Your info">
            </div>
            <div class="form-group">
              <label for="usrname"><span class="glyphicon glyphicon-user"></span> Send To</label>
              <input type="text" class="form-control" id="usrname" placeholder="Enter email">
            </div>
              <button type="submit" class="btn btn-block">Submit 
                <span class="glyphicon glyphicon-ok"></span>
              </button>
          </form>
        </div>
        <div class="modal-footer">
          <button type="submit" class="btn btn-danger btn-default pull-left" data-dismiss="modal">
            <span class="glyphicon glyphicon-remove"></span> Cancel
          </button>
          <p>Need <a href="#">help?</a></p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Container (Contact Section) -->
<div id="contact" class="container">
  <h3 class="text-center">Contact</h3>
  <p class="text-center"><em>We love our followers!</em></p>

  <div class="row">
    <div class="col-md-4">
      <p>Drop a note.</p>
      <p><span class="glyphicon glyphicon-map-marker"></span>Gharb, Gozo</p>
      <p><span class="glyphicon glyphicon-phone"></span>Phone: +00 1515151515</p>
      <p><span class="glyphicon glyphicon-envelope"></span>Email: mail@mail.com</p>
    </div>
    <div class="col-md-8">
      <div class="row">
        <div class="col-sm-6 form-group">
          <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>
        </div>
        <div class="col-sm-6 form-group">
          <input class="form-control" id="email" name="email" placeholder="Email" type="email" required>
        </div>
      </div>
      <textarea class="form-control" id="comments" name="comments" placeholder="Comment" rows="5"></textarea>
      <br>
      <div class="row">
        <div class="col-md-12 form-group">
          <button class="btn pull-right" type="submit">Send</button>
        </div>
      </div>
    </div>
  </div>
  <br>
  <h3 class="text-center">From The Blog</h3>  
  <ul class="nav nav-tabs">
    <li class="active"><a data-toggle="tab" href="#home">Mark</a></li>
    <li><a data-toggle="tab" href="#menu1">Ilaria</a></li>
    <li><a data-toggle="tab" href="#menu2">Lisa</a></li>
  </ul>

  <div class="tab-content">
    <div id="home" class="tab-pane fade in active">
      <h2>Mark McIntosh</h2>
      <p>Man, we've been on the road for some time now. Looking forward for a healthier future.</p>
    </div>
    <div id="menu1" class="tab-pane fade">
      <h2>Ilaria Sant</h2>
      <p>Always a pleasure people! Hope you enjoyed our plan</p>
    </div>
    <div id="menu2" class="tab-pane fade">
      <h2>Lisa Scott</h2>
      <p>I mean, sometimes I enjoy my job, helping people out of old habbits.</p>
    </div>
  </div>
</div>

<!-- Image of location/map -->
<img src="map.jpg" class="img-responsive" style="width:100%">

<!-- Footer -->
<footer class="text-center">
  <a class="up-arrow" href="#myPage" data-toggle="tooltip" title="TO TOP">
    <span class="glyphicon glyphicon-chevron-up"></span>
  </a><br><br>
  <p>Bootstrap Theme Made By <a href="https://www.w3schools.com" data-toggle="tooltip" title="Visit w3schools">www.w3schools.com</a></p> 
</footer>

<script>
$(document).ready(function(){
  // Initialize Tooltip
  $('[data-toggle="tooltip"]').tooltip(); 
  
  // Add smooth scrolling to all links in navbar + footer link
  $(".navbar a, footer a[href='#myPage']").on('click', function(event) {

    // Make sure this.hash has a value before overriding default behavior
    if (this.hash !== "") {

      // Prevent default anchor click behavior
      event.preventDefault();

      // Store hash
      var hash = this.hash;

      // Using jQuery's animate() method to add smooth page scroll
      // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area
      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){
   
        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
      });
    } // End if
  });
})
</script>

</body>
</html>
