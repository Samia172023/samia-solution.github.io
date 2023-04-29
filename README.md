# samia-solution.github.io
@media only screen and (min-width: 992px) {
    .desktop {
      display: block;
    }
  }
  @media only screen and (min-width: 768px) and (max-width: 991px) {
     .tablet {
      display: block;
    }
  }
  
  @media only screen and (max-width: 767px) {
    .mobile {
      display: block;
    }
  }
  .gauche{
    float:left;
    width:32%;
}
.droite{
    float:right;
    width:32%;
}

.center{
    float:left;
    width:32%;
}


.box {
	flex-basis: 30%;
	margin-bottom: 20px;
	padding: 20px;
	background-color: #f5f5f5;
	border: 1px solid #ccc;
}

@media screen and (max-width: 991px) {
	.box {
		flex-basis: 47%;
	}
}

@media screen and (max-width: 767px) {
	.box {
		flex-basis: 100%;
	}
}

.container {
        margin: 0 20px; /* or any desired value */

    display: flex;
    flex-wrap: wrap;
  }
  
  .box {
    flex-basis: 50%;
    box-sizing: border-box;
    padding: 20px;
  }
  
  .full-width {
    flex-basis: 100%;
  }
  
  @media screen and (max-width: 991px) and (min-width: 768px) {
    .box {
      flex-basis: 100%;
    }
  }

  
  @media screen and (max-width: 767px) {
    .section {
      width: 100%;
      float: none;

    }

  }
  .section-title {
align-items: center;
  top: 0;
  right: 0;
    color: #fff;
    font-size: 1.2em;
    padding: 0.5em 5em;
  }
  section {
    position: relative;
    padding-top: 1em;
    margin-bottom: 1.5em;
    padding: 20px;
    
  }
  div section{
    background-color: grey;
    font-size: 18px;
    margin-top: 20px;
  }
  section {
    border: 1px solid black;
  }

  .section-1 {
    background-color: rgb(255, 98, 0);
    border: 1px solid black;
  }  
  .section-2 {
    background-color: skyblue;
    border: 1px solid black;
  }  
  .section-3 {
    background-color: red;
    border: 1px solid black;
  }  
  h2{
    text-align: center;
    font-size: 30px;
  }
  
  <!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My website</title>
  <link rel="stylesheet" href="mod.css">
</head>
<body>
  <header>
    <h2>HELLOO THIS IS MY WEBSITE </h2>
  </header>
  <hr>
  <div class="gauche">
    <section class="section-1">
    <div class="section-title">BEEF</div></section><section>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id dui lacus. Sed maximus nibh sed aliquet malesuada.</p>
  </section></div> 
  <div class="center">
    <section class="section-2">
    <div class="section-title"> Sushi </div></section><section>
    <p>Phasellus vel magna bibendum, faucibus velit sit amet, mattis augue. Sed lobortis diam nec lorem hendrerit dignissim.</p>
  </section></div>
  <div class="gauche">
    <section class="section-3">
    <div class="section-title">Chicken</div></section><section>
    <p>Vestibulum ut commodo nunc. Praesent tincidunt faucibus, ut vestibulum arcu babhu in. Donec tincidunt orci ut eros auctor, nec feugiat nisi hendrerit.</p>
  </section></div>
</body>
</html>

