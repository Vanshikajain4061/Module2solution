<!doctype html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" href="stylesheet.css">
    <title>Assignment Solution for Module 2</title>
</head>

<body>

<div class="title-container">Our Menu</div>

<div class="row">
  <div class="col-lg-4 col-md-6 col-sm-12">
  <div class='menu'> 
  <div class='menu-title' id="chicken">Chicken</div>
  <p class='text'>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus 
  magna. Cras 
  in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur 
  massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, 
  at luctus turpis elit sit amet quam. Vivamus pretium ornare est.</p>
  </div>
  </div>


  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class='menu'> 
     <div class='menu-title' id="beef">
     Beef
     </div>
     <p class='text'>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus 
     magna. Cras 
     in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur 
     massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.
     </p>
    </div>
  </div>

  <div class="col-lg-4 col-md-12 col-sm-12">
    <div class='menu'>
      <div class='menu-title' id="sushi">Sushi</div>
      <p class='text'>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
      Vivamus magna. Cras 
      in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur 
      massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, 
      at luctus turpis elit sit amet quam. Vivamus pretium ornare est.
      </p>
    </div>
  </div>



   
</div>


</body>
</html>
*{font-family:"Comic Sans MS", cursive, sans-serif;
  box-sizing: border-box;}

	.title-container {
  width: 90%;
  height: 100px;
  margin-right: auto;
  margin-left: auto;
  text-align: center;
  font-size: 175%;
  }

   .menu-title{
   	width:40%;
   	float:right;
   	border: 2px solid black;
   	text-align: center;
   	font-size: 125%;
   	float:right;
   }

   .menu{
   	background-color: #8e8e8e;
   	margin:10px;
   	border:2px solid black;
   }

   .text{
   	margin:10px;
   	margin-top:40px;
   	clear:both;
   }

   .row {
    width: 90%;
    border: 5px;
    margin-right: auto;
    margin-left: auto;
    padding:5px;
   }
   #chicken{background-color: #cf8d8d;}
   #beef{background-color: #b93c3b; color:white;}
   #sushi{background-color: #e1ca8d;}
   

/********** Desktop **********/
@media (min-width: 992px) {
  .col-lg-4 {
    float: left;
    background-color: white;
    width: 33.33%;
  }
}

/********** Tablet **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6, .col-md-12 {
    float: left;
    background-color: white;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-12 {
    width: 100%;
  }
}

/********** Mobile **********/
@media (max-width: 767px) {.col-sm-12 {
    float: left;
    background-color: white;
    width: 100%;}
}
