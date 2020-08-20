### Hi there 👋

<!--
**Rohit-hooda/Rohit-Hooda** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
-->
##  I’m currently working on projects in Web Development.
## I’m currently learning JavaScript
## 👯 I’m looking to collaborate on few intresting web project.
## 🤔 I’m looking for help with ...
## 💬 Ask me about anything!
## 📫 How to reach me: rohithooda1999@gmail.com
## ⚡ Fun fact: Banging your head against a code for one hour burns 150 calories.

<!DOCTYPE html>
<html>
<head>
	<title>Rohit Hooda</title>
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1" />
	<link href="https://fonts.googleapis.com/css2?family=Russo+One&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&family=Russo+One&display=swap" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="default.css">
	<link id="theme-style" rel="stylesheet" type="text/css" href="">
</head>
<body>
	<section class="s1">
		<div class="main-container">
			<div class="greeting-wrapper">
				<h1>Hi, I'm Rohit Hooda</h1>
			</div>

			<div class="intro-wrapper">
				<div class="nav-wrapper">

					<!-- Link around dots-wrapper added after tutorial video -->
					<a href="index.html">
						<div class="dots-wrapper">
							<div id="dot-1" class="browser-dot"></div>
							<div id="dot-2" class="browser-dot"></div>
							<div id="dot-3" class="browser-dot"></div>
						</div>
					</a>

					<ul id="navigation">
						<li><a href="index.html#contact">Contact</a></li>
					</ul>
				</div>

				<div class="left-column">
					<img id="profile_pic" src="images/rohit.png">
					<h5 style="text-align: center;line-height: 0;">Personalize Theme</h5>

					<div id="theme-options-wrapper">
						<div data-mode="light" id="light-mode" class="theme-dot"></div>
						<div data-mode="black" id="black-mode" class="theme-dot"></div>
						<div data-mode="yellow" id="yellow-mode" class="theme-dot"></div>
					</div>

					<p id="settings-note">*Theme settings will be saved for<br>your next vist</p>
				</div>

				<div class="right-column">

					<div id="preview-shadow">
						<div id="preview">
							<div id="corner-tl" class="corner"></div>
							<div id="corner-tr" class="corner"></div>
							<h3>What I Do</h3>
							<p>I was a lead developer in a past life, now I enjoy teaching courses.</p>
							<div id="corner-br" class="corner"></div>
							<div id="corner-bl" class="corner"></div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section class="s2">
		<div class="main-container">

			<div class="about-wrapper">
				<div class="about-me">
					<h4>More about me</h4>
					<p>I build new projects just to tickle my brain and love teaching others how they're made.</p>
					<p>write something about yourself</p>
					<hr>
					<h4>EXPERTISE</h4>
					<p>Fullstack developer<a target="_blank" href="resume.pdf">Download Resume</a></p>
					<div id="skills">
						<ul>
							<li>Python</li>
							<li>Java</li>
							<li>JavaScript</li>
							<li>Node</li>
							<li>Postgres</li>
						</ul>
						<ul>
							<li>AWS (RDS/S3/EC2)</li>
							<li>Heroku</li>
							<li>HTML/CSS</li>
						</ul>
					</div>
				</div>
				
				<div class="social-links">
					<img id="social_img" src="images/linkedin.png">
					<h3>Find me on LinkedIn and GitHub</h3>

					<a target="_blank" href="https://www.linkedin.com/in/rohit-hooda/">LinkedIn: @Rohit Hooda</a>
					<br>
					<a target="_blank" href="https://github.com/Rohit-hooda">GitHub: @Rohit-Hooda</a>
				</div>
			</div>

		</div>
	</section>

	<section class="s1">
		<div class="main-container">
			<h3 style="text-align: center;">Some of my past projects</h3>

			<div class="post-wrapper">

				<div>
					<div class="post">
						<img class="thumbnail" src="images/dash.jpg">
						<div class="post-preview">
							<h6 class="post-title">Laboratory Management System</h6>
							<p class="post-intro">Designed built & mantained a the lab managment system for FOI Laboratories</p>
							<a href="post.html">Read More</a>
						</div>
					</div>
				</div>

				<div>
					<div class="post">
						<img class="thumbnail" src="images/ecom.jpg">
						<div class="post-preview">
							<h6 class="post-title">Online Store - CoursePost Title</h6>
							<p class="post-intro">Online store with paypal payments intergration and guest user shopping</p>
							<a href="post.html">Read More</a>
						</div>
					</div>
				</div>

				<div>
					<div class="post">
						<img class="thumbnail" src="images/membership site.jpg">
						<div class="post-preview">
							<h6 class="post-title">Membership Website</h6>
							<p class="post-intro">Modulized guide for online courses with step by  step intructions</p>
							<a href="post.html">Read More</a>
						</div>
					</div>
				</div>

			</div>
		</div>
	</section>

	<section class="s2">
		<div class="main-container">
			<a href=""></a>
			<h3 style="text-align: center;">Get In Touch</h3>

			<form id="contact-form">
				<a name="contact"></a>

				<label>Name</label>
				<input class="input-field" type="text" name="name">

				<label>Subject</label>
				<input class="input-field" type="text" name="subject">

				<label>Email</label>
				<input class="input-field" type="text" name="email">

				<label>Message</label>
				<textarea class="input-field" name="message"></textarea>

				<input id="submit-btn" type="submit" value="Send">
			</form>
		</div>
	</section> 

	<script type="text/javascript" src="script.js"></script>
</body>
</html>
