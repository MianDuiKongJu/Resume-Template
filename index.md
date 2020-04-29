<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Doe Resume Template</title>
  <link rel="stylesheet" href="css/bootstrap.min.css" type="text/css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
  <link rel="stylesheet" href="css/pageCSS.css" type="text/css">
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
