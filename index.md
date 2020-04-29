<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Doe Resume Template</title>
  <link rel="stylesheet" href="css/bootstrap.min.css" type="text/css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
  	<style>
		* {
			font-family: 'Roboto', sans-serif;
		}
		body{
			background-color: #f5f5f5;
			background-image: url(https://hades217.github.io/images/main_bg.png);
			background-size: cover;
			background-repeat: no-repeat;
			margin-left:40px;
			margin-right:40px;
		}
		.greenWords{
			color:#2eca7f;
		}
		.site__headerContent{
			margin-top:30px;
			margin-left:auto;
			margin-right:auto;
			width:100%;
			height:80px;
			background-color: transparent;
			max-width: 1032px;
			text-align: center;
		}
		.site__headerTittle{
			font-size:1.2rem;
			position: relative;
			float:left;
		}
		.site__headerNav{
			display:flex;
			flex-direction: row;
			position:relative;
			float:right;
		}
		.site_headerNavList{
			display:inline-block;
			text-align: center;
			padding-left: 10px;
			padding-right:10px;
      			opacity: 0.6;
		}
		.site__headerNavLink{
			color:rgb(165, 165, 165);
      			transition: all 0.3s ease-in-out;
		}
    		.site__headerNavLink::after{
		      	content: "";
		     	border-bottom: 3px solid #2eca7f;
		      	width: 0px;
		      	display: block;
		      	margin: auto;
		      	margin-top: 3px;
		     	transition: width 0.5s ease-in-out;
    		}
		.site__headerNavLink:hover{
			opacity: 1;
      			text-decoration: none;
      			color: black;
		}
    		.site__headerNavLink:hover::after{
     			width: 30px;
   		}
    		.navClicked {
      			color: black;
    		}
    		.navClicked:after{
		      	content: "";
		      	border-bottom: 3px solid #2eca7f;
		      	width: 30px;
		      	display: block;
		      	margin: auto;
		     	 margin-top: 3px;
  		}
		.home{
			max-width: 1032px;
			width:100%;
			margin-left: auto;
			margin-right:auto;
		}
		.home__header{
			background-color: #2eca7f;
			padding:30px;
			margin-bottom: 30px;
			border-radius: 10px 10px 0 0;
			display: flex;
			flex-wrap: wrap;
			box-shadow: 3px 3px 10px gray;
		}
		.home__headerImage{
			border: 5px solid white;
			margin-bottom:-80px;
			max-width: 280px;
			transition: all 0.6s ease-in-out;
			align-content: center;
			box-shadow: 2px 2px 2px lightgray;
		}
		.home__headerImage:hover{
			opacity: 97%;
			box-shadow: 5px 8px 10px gray;
			transform:translateY(-10px);
			cursor: pointer;
		}
		img{
			align-content: center;
			max-width: 100%;
			height:auto;
			vertical-align:bottom;
		}
		.home__header-right__main{
			text-align: center;
			color:white;
			margin-top:30px;
		}
		.home__header-right__main>h1{
			font-size: 3.7rem;
			font-weight: 700;
		}
		.home__header-right__dynamicRoleDisplay{
			font-weight: 600;
			font-size: 1.2rem;
		}
		.home__header-right__links{
			display:flex
			flex-wrap:wrap;
			text-align:center;
			margin-top:20px;
		}
		i{
			border: 10px solid white;
			border-radius: 50%;
			background-color: white;
		}
		.home__content{
			padding-top:80px;
			margin-top: -30px;
			border-radius: 0 0 10px 10px;
			display:flex;
			flex-wrap:wrap;
			background-color: white;
			padding-bottom: 40px;
			box-shadow: 3px 3px 10px gray;
		}
		/* .home__contentIntro{
			margin-left: -20px;
		} */
		.aboutMe{
			font-size: 1.2rem;
			font-weight: 700;
			margin-left: 10px;
		}
		.aboutMeContent{
			font-size: 0.8rem;
			font-weight: 400;
			margin-left: 10px;
		}
		.listDotFree{
			list-style: none;
		}
		.home__contentTittle{
			min-width:120px;
			text-align: left;
			margin-left:-50px;
			display:inline-flex;
			font-size: 0.9rem;
		}
		.home__contentValue{
			text-align: left;
			color: gray;
		}
		.linkColor{
			color: #2eca7f;
			text-decoration: blue;
			transition: all 0.3s ease-in-out;
		}
		.linkColor:hover{
			color:orange;
			text-decoration: none;
		}
    		.resume {
			max-width: 1032px;
			width: 100%;
			margin: auto;
		}
		.resume__header {
			background-color: #2eca7f;
			padding-top: 25px;
			color: white;
			text-align: center;
			border-radius: 10px 10px 0 0;
			height: 100px;
			box-shadow: 3px 3px 10px gray;
		}
		.resume__content {
			background-color: white;
			border-radius: 0 0 10px 10px;
			padding: 15px;
			box-shadow: 3px 3px 10px gray;
		}
		.resume__tittle {
			font-size: 1.2rem;
			font-weight: 400;
			padding-top: 10px;
			padding-left: 5px;
		}
		.resume__education {
			margin: 15px;
		}
		.resume__topBlockLeftLine {
			border-left: 3px solid gray;
		}
		.resume__introductionBlock {
			box-shadow: 1px 1px 2px gray;
			border: 0px solid black;
			border-left: 3px solid #2eca7f;
			padding: 15px;
			padding-top: 0px;
			padding-bottom: 0px;
			margin-left: 20px;
			margin-top: 10px;
		}
		.resume__introductionBlock:before {
			content:"";
			border: 2px solid #2eca7f;
			border-radius: 50%;
			display:inline-block;
			height: 15px;
			width: 15px;
			position: relative;
			background-color: white;
			right: 47px;
			top: 20px;
		}
		.resume__introductionBlock:after {
			content:"__";
			display:inline-block;
			color:#2eca7f;
			position:relative;
			right: 32px;
			bottom: 153px;
		}
		.resume__introductionBlock:hover {
			box-shadow: 1px 1px 5px black;
		}
		.resume__introductionBlock:hover::before {
			content:"";
			border: 2px solid #2eca7f;
			border-radius: 50%;
			display:inline-block;
			height: 19px;
			width: 19px;
			position: relative;
			background-color: #2eca7f;
			right: 49px;
			top: 22px;
		}
		.resume__highlightPeriod {
			color: #2eca7f;
      			font-size: 0.9rem;
		}
		.resume__uniNameCompanyName {
			opacity: 0.5;
     			font-size: 0.9em;
		}
    		.resume__introduction{
      			font-size: 0.8rem;
      			padding-top: 8px;
    		}
		.resume__uniNameCompanyName:before {
			content:"|  "
		}
		.resume__powerBlock {
			padding-top: 10px;
			padding-bottom: 20px;
		}
		.resume__powerContainer {
			border: 2px solid lightgray;
			width: 95%;
			height:13px;
		}
		.resume__powerLineWebDesign {
			border: 3px solid #2eca7f;
			background: #2eca7f;
			height: 10px;
			width: 85%;
			animation: powerUpWeb 1s;
		}
		.resume__powerLineGraphicDesign {
			border: 3px solid #2eca7f;
			background: #2eca7f;
			height: 10px;
			width: 70%;
			animation: powerUpGraphic 1s;
		}
		.resume__powerLinePrintDesign {
			border: 3px solid #2eca7f;
			background: #2eca7f;
			height: 10px;
			width: 80%;
			animation: powerUpPrint 1s;
		}
		.resume__powerLineHTML5 {
			border: 3px solid #2eca7f;
			background: #2eca7f;
			height: 10px;
			width: 95%;
			animation: powerUpHTML 1s;
		}
		.resume__powerLineCSS3 {
			border: 3px solid #2eca7f;
			background: #2eca7f;
			height: 10px;
			width: 90%;
			animation: powerUpCSS 1s;
		}
		.resume__powerLineJQ{
			border: 3px solid #2eca7f;
			background: #2eca7f;
			height: 10px;
			width: 65%;
			animation: powerUpJQ 1s;
		}
		@keyframes powerUpWeb {
			from {
				width:1%
			}
				to {
					width:85%
				}
		}
		@keyframes powerUpGraphic {
			from {
				width:1%
			}
				to {
					width:70%
				}
		}
		@keyframes powerUpPrint {
			from {
				width:1%
			}
				to {
					width:80%
				}
		}
		@keyframes powerUpHTML {
			from {
				width:1%
			}
				to {
					width:95%
				}
		}
		@keyframes powerUpCSS {
			from {
				width:1%
			}
				to {
					width:90%
				}
		}
		@keyframes powerUpJQ {
			from {
				width:1%
			}
				to {
					width:65%
				}
		}
   		.hide {
     			display: none;
    		}
	</style>
</head>
<body>
	<header>
		<div class="site__headerContent">
			<div class="site__headerTittle">
				John 
				<span class="greenWords">Doe</span>
			</div>
			<div class="site__headerNav">
				<ul">
					<li class="site_headerNavList">
						<a href=# id="home"class="site__headerNavLink navClicked">
							Home
						</a>
					</li>
					<li class="site_headerNavList">
						<a href=# id="resume" class="site__headerNavLink">
							Resume
						</a>
					</li>
					<li class="site_headerNavList">
						<a href=# id="services"class="site__headerNavLink">
							Services
						</a>
					</li>
					<li class="site_headerNavList">
						<a href=# id="blog" class="site__headerNavLink">
							Blog
						</a>
					</li>
					<li class="site_headerNavList">
						<a href=# id="contact" class="site__headerNavLink">
							Contact
						</a>
					</li>
				</ul>
			</div>
	
		</div>
	</header>
	<main id="homePage" class="home">
    <div class="home__header">
				<div class="col-sm-4 col-md-4 col-ld-4">
					<!-- left part for photo -->
					<div class="home__headerImage">
						<!-- for personal image -->
						<img src="Image/John Doe.png" alt="Resume Image">
					</div>
				</div>
				<div class="col-sm-8 col-md-8 col-ld-8">
					<!-- right part for name role and links -->
					<div class="home__header-right__main">
						<!-- Resume name here -->
						<h1>
							<!-- Resume main name with Heading1 here -->
							John Doe
						</h1>
						<div class="home__header-right__dynamicRoleDisplay" id="roleDisplay">
							<!-- Resume roles showing with two div which only shows one at the same time -->
							<!-- use setInterval to automatically changing the role showing -->
							Fronted-Developer
						</div>
					</div>
					<div class="home__header-right__links">
						<!-- social media links here -->
						<a href=#>
							<!-- for twitter -->
							<i class="fab fa-twitter"></i>
						</a>
						<a href=#>
							<!-- for facebook -->
							<i class="fab fa-facebook"></i>
						</a>
						<a href=#>
							<!-- for instagram -->
							<i class="fab fa-instagram"></i>
						</a>
					</div>
				</div>
		</div>
		<div class="home__content">
			<div class="col-sm-6 col-md-6 col-lg-6">
				<!-- left part for personal introduction -->
				<h3 class="aboutMe">
					<!-- above part -->
					About 
					<span class="greenWords">Me</span>
				</h3>
				<p class="aboutMeContent">
					<!-- personal introduction part -->
					Hello! I’m John Doe. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean fermentum ullamcorper sem, at placerat dolor volutpat ac. Duis nulla enim, condimentum nec ultricies.
				</p>
			</div>
			<div class="col-sm-6 col-md-6 col-lg-6">
				<!-- right part with age residence address email & phone -->
				<ul class="listDotFree">
					<li>
						<span class="home__contentTittle">
							Age:
						</span>
						<span class="home__contentValue">
							29
						</span>
					</li>
					<li>
						<span class="home__contentTittle">
							Residence:
						</span>
						<span class="home__contentValue">
							Australia
						</span>
					</li>
					<li>
						<span class="home__contentTittle">
							Address:
						</span>
						<span class="home__contentValue">
							Level 3 / 57 Coronation Drive, Brisbane
						</span>
					</li>
					<li>
						<span class="home__contentTittle">
							e-mail:
						</span>
						<span class="home__contentValue">
							<a href=# class="linkColor">
								info@jiangren.com.au
							</a>
						</span>
					</li>
					<li>
						<span class="home__contentTittle">
							Phone:
						</span>
						<span class="home__contentValue">
							+0123 123 456 789
						</span>
					</li>
				</ul>
			</div>
		</div>
  </main>
  <main id="resumePage" class="resume hide">
    <div class="resume__header">
			<h1 style="font-weight: 700;">Resume</h1>
		</div>
		<div class="resume__content">
			<div class="row">
				<div class="col-sm-6 col-md-6 col-lg-6">
					<div class="resume__tittle">
						Education
					</div>
					<div class="resume__education resume__topBlockLeftLine">
						<div class="resume__introductionBlock">
							<div class="resume__greenCircle1"> </div>
							<h5>
								<!-- space for course name -->
								CourseA
							</h5>
							<span class="resume__highlightPeriod">
								<!-- space for period -->
								2018
							</span>
							<span class="resume__uniNameCompanyName">
								<!-- space for name of university -->
								University of Newcastle
							</span>
							<p class="resume__introduction">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora suscipit nemo non. Molestias voluptatum adipisci minima! Voluptatibus ratione reprehenderit perferendis!</p>
						</div>
						<div class="resume__introductionBlock">
							<div class="resume__greenCircle2"> </div>
							<h5>
								CourseB
							</h5>
							<span class="resume__highlightPeriod">
								<!-- space for period -->
								2019
							</span>
							<span class="resume__uniNameCompanyName">
								<!-- space for name of university -->
								Jiangren Academy
							</span>
							<p class="resume__introduction">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora suscipit nemo non. Molestias voluptatum adipisci minima! Voluptatibus ratione reprehenderit perferendis!</p>
						</div>
						<div class="resume__introductionBlock">
							<h5>
								<!-- space for course name -->
								CourseC
							</h5>
							<span class="resume__highlightPeriod">
								<!-- space for period -->
								2020
							</span>
							<span class="resume__uniNameCompanyName">
								<!-- space for name of university -->
								RMIT
							</span>
							<p class="resume__introduction">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora suscipit nemo non. Molestias voluptatum adipisci minima! Voluptatibus ratione reprehenderit perferendis!</p>
						</div>
					</div>
				</div>
				<div class="col-sm-6 col-md-6 col-lg-6">
					<div class="resume__tittle">
						Experience
					</div>
					<div class="resume__education resume__topBlockLeftLine">
						<div class="resume__introductionBlock">
							<h5>
								<!-- space for Job Tittle -->
								Tittle1
							</h5>
							<span class="resume__highlightPeriod">
								<!-- space for period -->
								Dec 2012 - Current
							</span>
							<span class="resume__uniNameCompanyName">
								<!-- space for company name -->
								xxx Company
							</span>
							<p class="resume__introduction">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora suscipit nemo non. Molestias voluptatum adipisci minima! Voluptatibus ratione reprehenderit perferendis!</p>
						</div>
						<div class="resume__introductionBlock">
							<h5>
								<!-- space for Job Tittle -->
								Tittle2
							</h5>
							<span class="resume__highlightPeriod">
								<!-- space for period -->
								Jun 2018 - Jun 2019
							</span>
							<span class="resume__uniNameCompanyName">
								<!-- space for company name -->
								xxx company2
							</span>
							<p class="resume__introduction">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora suscipit nemo non. Molestias voluptatum adipisci minima! Voluptatibus ratione reprehenderit perferendis!</p>
						</div>
						<div class="resume__introductionBlock">
							<h5>
								<!-- space for Job Tittle -->
								Tittle3
							</h5>
							<span class="resume__highlightPeriod">
								Dec 2017 - Dec 2018
								<!-- space for period -->
							</span>
							<span class="resume__uniNameCompanyName">
								<!-- space for company name -->
								xxx company3
							</span>
							<p class="resume__introduction">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora suscipit nemo non. Molestias voluptatum adipisci minima! Voluptatibus ratione reprehenderit perferendis!</p>
						</div>
					</div>
				</div>
			</div>
			<div class="row">
				<div class="col-sm-6 col-md-6 col-lg-6">
					<div class="resume__tittle">Design Skills</div>
					<div class="resume__powerBlock">
							<h6>Web Design</h6>
							<div class="resume__powerContainer">
								<div class="resume__powerLineWebDesign">
									<!-- space for the power line -->
								</div>
							</div>
							<h6>Graphic Design</h6>
							<div class="resume__powerContainer">
								<div class="resume__powerLineGraphicDesign">
									<!-- space for the power line -->
								</div>
							</div>
							<h6>Print Design</h6>
							<div class="resume__powerContainer">
								<div class="resume__powerLinePrintDesign">
									<!-- space for the power line -->
								</div>
							</div>
					</div>
				</div>
				<div class="col-sm-6 col-md-6 col-lg-6">
					<div class="resume__tittle">Coding Skills</div>
					<div class="resume__powerBlock">
						<h6>HTML5</h6>
						<div class="resume__powerContainer"> 
							<div class="resume__powerLineHTML5">
								<!-- space for the power line -->
							</div>
						</div>
						<h6>CSS3/SASS</h6>
						<div class="resume__powerContainer">
							<div class="resume__powerLineCSS3">
								<!-- space for the power line -->
							</div>
						</div>
						<h6>jQuery</h6>
						<div class="resume__powerContainer">
							<div class="resume__powerLineJQ">
								<!-- space for the power line -->
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</main>
	<footer>
		<!-- for feature JavaScript -->
		<script>
			const tittleChange = document.getElementById('roleDisplay')
      let i = 0;
			function changeTittle(){
				if(i == 0){
					i = 1;
					tittleChange.innerHTML = "Fronted-Developer";
				}
				else{
					i = 0;
					tittleChange.innerHTML = "Web Designer";
				}
			}
			setInterval("changeTittle()",3000);
      document.querySelector('#services').addEventListener('click', ()=>{alert('Services page is not finished yet')})
      document.querySelector('#blog').addEventListener('click', ()=>{alert('Blog page is not finished yet')})
      document.querySelector('#contact').addEventListener('click', ()=>{alert('Services page is not finished yet')})
      // function fn(){
      //   var previous = '';
      //   var current = 'home'
      //   changeNavItem();
      //   function changeNavItem(){
      //     if(previous) {
      //       var previousNavItem = document.querySelector('')
      //     }
      //   }
      // } 研究完龙哥的js后更改
      function clickHome(){
        document.querySelector('#home').classList.add('navClicked');
        document.querySelector('#resume').classList.remove('navClicked');
        document.querySelector('#homePage').classList.remove('hide');
        document.querySelector('#resumePage').classList.add('hide');
      }
      document.querySelector('#home').addEventListener('click', clickHome);
      function clickResume(){
        document.querySelector('#home').classList.remove('navClicked');
        document.querySelector('#resume').classList.add('navClicked');
        document.querySelector('#homePage').classList.add('hide');
        document.querySelector('#resumePage').classList.remove('hide');
      }
      document.querySelector('#resume').addEventListener('click', clickResume);
		</script>
	</footer>
</body>
</html>
