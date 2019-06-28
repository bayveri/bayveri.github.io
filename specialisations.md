---
layout: page
title: Specialisations
subtitle: Formal Education Just Show Us! We Learn Them Later.
---

<html lang="en" >

<head>
  <meta charset="UTF-8">
  <title>Bayveri's Timeline</title>
  
<style type="text/css" media="screen">

body {	
  margin: 0;
  padding: 0;
  background: rgb(230,230,230);
  
  color: rgb(50,50,50);
  font-family: 'Open Sans', sans-serif;
  font-size: 140%;
  line-height: 1.8em;
}

/* ================ The Timeline ================ */

.timeline {
  position: relative;
  width: 660px;
  margin: 0 auto;
  margin-top: 20px;
  padding: 1em 0;
  list-style-type: none;
}

.timeline:before {
  position: absolute;
  left: 50%;
  top: 0;
  content: ' ';
  display: block;
  width: 6px;
  height: 100%;
  margin-left: -3px;
  background: rgb(80,80,80);
  background: -moz-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(30,87,153,1)), color-stop(100%,rgba(125,185,232,1)));
  background: -webkit-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: -o-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: -ms-linear-gradient(top, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  background: linear-gradient(to bottom, rgba(80,80,80,0) 0%, rgb(80,80,80) 8%, rgb(80,80,80) 92%, rgba(80,80,80,0) 100%);
  
  z-index: 5;
}

.timeline li {
  padding: 1em 0;
}

.timeline li:after {
  content: "";
  display: block;
  height: 0;
  clear: both;
  visibility: hidden;
}

.direction-l {
  position: relative;
  width: 300px;
  float: left;
  text-align: right;
}

.direction-r {
  position: relative;
  width: 300px;
  float: right;
}

.flag-wrapper {
  position: relative;
  display: inline-block;
  
  text-align: center;
}

.flag {
  position: relative;
  display: inline;
  background: rgb(248,248,248);
  padding: 6px 10px;
  border-radius: 5px;
  
  font-weight: 600;
  text-align: left;
}

.direction-l .flag {
  -webkit-box-shadow: -1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  -moz-box-shadow: -1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  box-shadow: -1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
}

.direction-r .flag {
  -webkit-box-shadow: 1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  -moz-box-shadow: 1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
  box-shadow: 1px 1px 1px rgba(0,0,0,0.15), 0 0 1px rgba(0,0,0,0.15);
}

.direction-l .flag:before,
.direction-r .flag:before {
  position: absolute;
  top: 50%;
  right: -40px;
  content: ' ';
  display: block;
  width: 12px;
  height: 12px;
  margin-top: -10px;
  background: #fff;
  border-radius: 10px;
  border: 4px solid rgb(255,80,80);
  z-index: 10;
}

.direction-r .flag:before {
  left: -40px;
}

.direction-l .flag:after {
  content: "";
  position: absolute;
  left: 100%;
  top: 50%;
  height: 0;
  width: 0;
  margin-top: -8px;
  border: solid transparent;
  border-left-color: rgb(248,248,248);
  border-width: 8px;
  pointer-events: none;
}

.direction-r .flag:after {
  content: "";
  position: absolute;
  right: 100%;
  top: 50%;
  height: 0;
  width: 0;
  margin-top: -8px;
  border: solid transparent;
  border-right-color: rgb(248,248,248);
  border-width: 8px;
  pointer-events: none;
}

.time-wrapper {
  display: inline;
  
  line-height: 1em;
  font-size: 0.9em;
  color: rgb(250,80,80);
  vertical-align: middle;
}

.direction-l .time-wrapper {
  float: left;
}

.direction-r .time-wrapper {
  float: right;
}

.time {
  display: inline-block;
  padding: 4px 6px;
  background: rgb(248,248,248);
}

.desc {
  margin: 1em 0.75em 0 0;
  
  font-size: 1.2em;
  font-style: italic;
  line-height: 1.5em;
}

.direction-r .desc {
  margin: 1em 0 0 0.75em;
}

/* ================ Timeline Media Queries ================ */

@media screen and (max-width: 660px) {

.timeline {
 	width: 100%;
	padding: 4em 0 1em 0;
}

.timeline li {
	padding: 2em 0;
}

.direction-l,
.direction-r {
	float: none;
	width: 100%;

	text-align: center;
}

.flag-wrapper {
	text-align: center;
}

.flag {
	background: rgb(255,255,255);
	z-index: 15;
}

.direction-l .flag:before,
.direction-r .flag:before {
  position: absolute;
  top: -30px;
	left: 50%;
	content: ' ';
	display: block;
	width: 12px;
	height: 12px;
	margin-left: -9px;
	background: #fff;
	border-radius: 10px;
	border: 4px solid rgb(255,80,80);
	z-index: 10;
}

.direction-l .flag:after,
.direction-r .flag:after {
	content: "";
	position: absolute;
	left: 50%;
	top: -8px;
	height: 0;
	width: 0;
	margin-left: -8px;
	border: solid transparent;
	border-bottom-color: rgb(255,255,255);
	border-width: 8px;
	pointer-events: none;
}

.time-wrapper {
	display: block;
	position: relative;
	margin: 4px 0 0 0;
	z-index: 14;
}

.direction-l .time-wrapper {
	float: none;
}

.direction-r .time-wrapper {
	float: none;
}

.desc {
	position: relative;
	margin: 1em 0 0 0;
	padding: 1em;
	background: rgb(245,245,245);
	-webkit-box-shadow: 0 0 1px rgba(0,0,0,0.20);
	-moz-box-shadow: 0 0 1px rgba(0,0,0,0.20);
	box-shadow: 0 0 1px rgba(0,0,0,0.20);
	
  z-index: 15;
}

.direction-l .desc,
.direction-r .desc {
	position: relative;
	margin: 1em 1em 0 1em;
	padding: 1em;
	
  z-index: 15;
}

}

@media screen and (min-width: 400px ?? max-width: 660px) {

.direction-l .desc,
.direction-r .desc {
	margin: 1em 4em 0 4em;
}

}
 /*hover effect*/
 a:hover img.timelineimage {
	opacity: 1;
	-webkit-animation: flash 1.5s;
	animation: flash 1.5s;
}
@-webkit-keyframes flash {
	0% {
		opacity: .4;
	}
	100% {
		opacity: 1;
	}
}
@keyframes flash {
	0% {
		opacity: .4;
	}
	100% {
		opacity: 1;
	}
}
 
 
 
 </style>

  
</head>

<body>

  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600,600italic,700,700italic' rel='stylesheet' type='text/css'>
  
<!-- The Timeline -->

<ul class="timeline">
	
		<!-- Programming Languages -->
<img class="heading" src="/img/heading1.png"/>
	<!-- R -->
<li>
	<a href="https://cran.r-project.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://cran.r-project.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/r.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">R</span>

				<span class="time-wrapper"><span class="time">2017 - present</span></span>
	
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/r_level.png"/> </div>
		</div>
	</li>
  
  
	<!-- Python -->
	<li>
	
	<a href="https://www.python.org/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.python.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/python.png"/></a>
	<br>
		<div class="direction-l">
		
			<div class="flag-wrapper">
				<span class="flag">PYTHON</span>
				
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc"> Level: Intermediate <br><img class="levelimage" src="/img/python_level.png"/> </div>
		</div>
	</li>
  
	<!-- SQL -->
	<li>
	
	<a href="https://www.mysql.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.mysql.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/sql.png"/></a>

	<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">SQL </span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/sql_level.png"/></div>
		</div>
	</li>

	<!-- HTML -->
	<li>
	  
	  <a href="https://www.w3schools.com/html/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.w3schools.com/html/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/html.png"/></a>
	  <br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">HTML</span>
				<span class="time-wrapper"><span class="time">2011 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/html_level.png"/> </div>
		</div>
	</li>
 
 	<!--MARKDOWN  -->
	<li>
	
	<a href="https://www.markdowntutorial.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.markdowntutorial.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/markdown.png"/></a>

	<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">MARKDOWN </span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/markdown_level.png"/></div>
		</div>
	</li>
 
 
	<!-- CSS -->
	<li>
	  
	  <a href="https://www.w3schools.com/css/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.w3schools.com/css/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/css.png"/></a>
	  <br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">CSS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/css_level.png"/></div>
		</div>
	</li>
 
	 <!--JAVASCRİPT  -->
	<li>
	
	<a href="https://www.javascript.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.javascript.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/javascript.png"/></a>

	<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">JAVA SCRIPT</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Pre-Intermediate <br><img class="levelimage" src="/img/javascript_level.png"/></div>
		</div>
	</li>
 
 
 	<!-- BOOTSTRAP -->
	<li>
	  
	  <a href="https://getbootstrap.com/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://getbootstrap.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/bootstrap.png"/></a>
	  <br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">BOOTSTRAP</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Pre-Intermediate <br><img class="levelimage" src="/img/bootstrap_level.png"/></div>
		</div>
	</li>
 
  	<!--YAML  -->
	<li>
	
	<a href="https://yaml.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://yaml.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/yaml.png"/></a>

	<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">YAML </span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/yaml_level.png"/></div>
		</div>
	</li>
 
 
 	<!-- XML -->
	<li>
	  
	  <a href="https://www.w3schools.com/xml/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.w3schools.com/xml/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/xml.png"/></a>
	  <br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">XML</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/xml_level.png"/></div>
		</div>
	</li>
 
 
 
  	<!--JSON  -->
	<li>
	
	<a href="https://www.json.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.json.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/json.png"/></a>

	<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">JSON</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/json_level.png"/></div>
		</div>
	</li>
 
 
 	<!-- BASH -->
	<li>
	  
	  <a href="https://www.gnu.org/software/bash/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.gnu.org/software/bash/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/bash.png"/></a>
	  <br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">BASH</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/bash_level.png"/></div>
		</div>
	</li>
	
	<!--MQL5  -->
	<li>
	
	<a href="https://www.mql5.com/en" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.mql5.com/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/mql5.png"/></a>

	<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">MQL5 </span>
				<span class="time-wrapper"><span class="time">2014 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/mql5_level.png"/></div>
		</div>
	</li>
 
 
		<!-- SOFTWARES -->
		<img class="heading" src="/img/heading2.png"/>
		
	<!-- MICROSOFT OFFICE -->	
	<li>
	<a href="https://www.office.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.office.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/office.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">MICROSOFT OFFICE SUIT</span>
				<span class="time-wrapper"><span class="time">2011 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/office_level.png"/></div>
		</div>
	</li>
	
	<!-- STATA -->
	<li>
	
	<a href="https://www.stata.com/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.stata.com/'); return false;"><img class="timelineimage" src="/img/stata.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">STATA</span>
				<span class="time-wrapper"><span class="time">2016 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/stata_level.png"/></div>
		</div>
	</li>
	
	<!-- EVIEWS -->	
	<li>
	<a href="https://www.eviews.com/home.html" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.eviews.com/home.html','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/eviews.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">EVIEWS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/eviews_level.png"/></div>
		</div>
	</li>
	
	<!-- INKSCAPE -->
	<li>
	
	<a href="https://inkscape.org/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://inkscape.org/'); return false;"><img class="timelineimage" src="/img/inkscape.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">INSCAPE</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/inkscape_level.png"/></div>
		</div>
	</li>
	
	<!-- GIMP -->	
	<li>
	<a href="https://www.gimp.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.gimp.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/gimp.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">GIMP</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/gimp_level.png"/></div>
		</div>
	</li>
	
	<!-- ADOBE ILLUSTRATOR -->
	<li>
	
	<a href="https://www.adobe.com/products/illustrator.html" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.adobe.com/products/illustrator.html'); return false;"><img class="timelineimage" src="/img/ai.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">ADOBE ILLUSTRATOR</span>
				<span class="time-wrapper"><span class="time">2019 - present</span></span>
			</div>
			<div class="desc">Level: Pre-Intermediate <br><img class="levelimage" src="/img/ai_level.png"/></div>
		</div>
	</li>
	
	
	<!-- BLENDER -->	
	<li>
	<a href="https://www.blender.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.blender.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/blender.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">BLENDER</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Pre-Intermediate <br><img class="levelimage" src="/img/blender_level.png"/></div>
		</div>
	</li>
	
	
	<!-- SCRIBUS -->
	<li>
	
	<a href="https://www.scribus.net/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.scribus.net/'); return false;"><img class="timelineimage" src="/img/scribus.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">SCRIBUS</span>
				<span class="time-wrapper"><span class="time">2019 - present</span></span>
			</div>
			<div class="desc">Level: Pre-Intermediate <br><img class="levelimage" src="/img/scribus_level.png"/></div>
		</div>
	</li>
	
	<!-- WORDPRESS -->	
	<li>
	<a href="http://www.roca.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('http://www.roca.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/wordpress.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">WORDPRESS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Upper-Intermediate <br><img class="levelimage" src="/img/wordpress_level.png"/></div>
		</div>
	</li>
	
	
	<!-- JEKYLL -->
	<li>
	
	<a href="https://jekyllrb.com/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://jekyllrb.com/'); return false;"><img class="timelineimage" src="/img/jekyll.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">JEKYLL</span>
				<span class="time-wrapper"><span class="time">2019 - present</span></span>
			</div>
			<div class="desc">Level: Upper-Intermediate <br><img class="levelimage" src="/img/jekyll_level.png"/></div>
		</div>
	</li>
	
	
	<!-- GITHUB -->	
	<li>
	<a href="https://github.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://github.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/github.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">GITHUB</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/github_level.png"/></div>
		</div>
	</li>
	
	<!-- METATRADER -->
	<li>
	
	<a href="https://www.metatrader5.com/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.metatrader5.com/en'); return false;"><img class="timelineimage" src="/img/metatrader.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">METATRADER</span>
				<span class="time-wrapper"><span class="time">2010 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/metatrader_level.png"/></div>
		</div>
	</li>
	
	
	<!-- TOOLS OF KALI LINUX -->	
	<li>
	<a href="https://www.kali.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.kali.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/kalilinux.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">KALI LINUX</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Pre-Intermediate <br><img class="levelimage" src="/img/kalilinux_level.png"/></div>
		</div>
	</li>
	
	
	<!-- DEBIAN -->
	<li>
	
	<a href="https://www.debian.org/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.debian.org/'); return false;"><img class="timelineimage" src="/img/debian.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">DEBIAN</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/debian_level.png"/></div>
		</div>
	</li>
	
	
	<!-- ORACLE VIRTUAL MACHINE -->	
	<li>
	<a href="https://www.virtualbox.org/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.virtualbox.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/virtualmachine.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">ORACLE VIRTUAL BOX</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Advance <br><img class="levelimage" src="/img/virtualmachine_level.png"/></div>
		</div>
	</li>
	
	
	<!-- DOCKER -->
	<li>
	
	<a href="https://www.docker.com/" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.docker.com/'); return false;"><img class="timelineimage" src="/img/docker.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">DOCKER</span>
				<span class="time-wrapper"><span class="time">2019 - present</span></span>
			</div>
			<div class="desc">Level: Beginner <br><img class="levelimage" src="/img/docker_level.png"/></div>
		</div>
	</li>
	
	<!-- CHROOT -->	
	<li>
	<a href="https://wiki.archlinux.org/index.php/chroot" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://wiki.archlinux.org/index.php/chroot','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/chroot.png"/></a>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">CHROOT</span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">Level: Intermediate <br><img class="levelimage" src="/img/chroot_level.png"/></div>
		</div>
	</li>
	
	<br>
	<br>
	
			<!-- Analytics -->
			<img class="heading" src="/img/heading3.png"/>
	
	<!-- STATISTICS -->
	<li>
	<a href="https://www.verianaliz.net/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/statistics.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">STATISTICS</span>
				<span class="time-wrapper"><span class="time">2010 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/statistics_level.png"/></div>
		</div>
	</li>
	
	<!-- MATHEMATICS -->
	<li>
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/anadolu.png"/></a>
	<br>
	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">MATHEMATICS</span>
				<span class="time-wrapper"><span class="time">2009 - present</span></span>
			</div>
			<div class="desc"> Level: Advanced <br><img class="levelimage" src="/img/mathematics_level.png"/></div>
		</div>
	</li>
	
	
	<!--ECONOMETRICS -->
	<li>
	<a href="https://www.verianaliz.net/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/econometrics.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">ECONOMETRICS</span>
				<span class="time-wrapper"><span class="time">2016 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/econometrics_level.png"/></div>
		</div>
	</li>
	
	
		<!-- DATA STRUCTER AND ALGORİTHMS -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/datastructure.png"/></a>
	<br>
	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">DATA STRUCTURE AND ALGORITHMS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc"> Level: Intermediate <br><img class="levelimage" src="/img/datastructure_level.png"/></div>
		</div>
	</li>
	
	
		<!--FINANCIAL STATEMENT ANALYSIS -->
		<li>
	<a href="https://www.verianaliz.net/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/financialstatement.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">FINANCIAL STATEMENT ANALYSIS</span>
				<span class="time-wrapper"><span class="time">2016 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/econometrics_level.png"/></div>
		</div>
	</li>
	
	
	<!-- VALUE CHAIN ANALYSIS  -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/valuechain.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">VALUE CHAIN ANALYSIS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc"> Level: Advanced <br><img class="levelimage" src="/img/valuechain_level.png"/></div>
		</div>
	</li>
	
	
	<!--TECHNICAL AND FUNDAMENTAL ANALYSIS -->
	<li>
	<a href="https://www.verianaliz.net/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/technicalanalysis.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">TECHNICAL AND FUNDAMENTAL ANALYSIS</span>
				<span class="time-wrapper"><span class="time">2016 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/technicalanalysis_level.png"/></div>
		</div>
	</li>
	
	
		<!-- WHAT IF ANALYSIS -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/whatif.png"/></a>
	<br>
	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">WHAT IF ANALYSIS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc"> Level: Advanced <br><img class="levelimage" src="/img/whatif_level.png"/></div>
		</div>
	</li>
	
	
		<!--COST ANALYSIS -->
		<li>
	<a href="https://www.verianaliz.net/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/costanalysis.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">COST ANALYSIS</span>
				<span class="time-wrapper"><span class="time">2016 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/costanalysis_level.png"/></div>
		</div>
	</li>
	
		<!-- CASH FLOW ANALYSIS -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/cashflow.png"/></a>
	<br>
	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">CASH FLOW ANALYSIS</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc"> Level: Advanced <br><img class="levelimage" src="/img/cashflow_level.png"/></div>
		</div>
	</li>
	
	
	<br>
	<br>
				<!-- LANGUAGES -->
				<img class="heading" src="/img/heading4.png"/>
	<!-- ENGLISH -->
	<li>
	<a href="https://www.hacettepe.edu.tr/english/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.hacettepe.edu.tr/english/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/english.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">ENGLISH</span>
				<span class="time-wrapper"><span class="time">2009 - present</span></span>
			</div>
			<div class="desc">Level: Advanced <br><img class="levelimage" src="/img/english_level.png"/></div>
		</div>
	</li>
	
	<!-- SPANISH -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/spanish.png"/></a>
	<br>
	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">SPANISH</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc"> Level: Pre-Intermediate <br><img class="levelimage" src="/img/spanish_level.png"/></div>
		</div>
	</li>	
	
	<!-- RUSSIAN -->
	<li>
	<a href="https://www.hacettepe.edu.tr/english/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.hacettepe.edu.tr/english/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/hacettepe.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">RUSSIAN</span>
				<span class="time-wrapper"><span class="time">2017 - present</span></span>
			</div>
			<div class="desc">Level: Elementory <br><img class="levelimage" src="/img/spanish_level.png"/></div>
		</div>
	</li>
	


		<br>
		<br>
				<!-- CERTIFICATIONS -->
				<img class="heading" src="/img/heading5.png"/>

	<!-- ENGLISH -->
	<li>
	<a href="https://www.hacettepe.edu.tr/english/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.hacettepe.edu.tr/english/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/hacettepe.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">ENGLISH</span>
				<span class="time-wrapper"><span class="time">2009 - present</span></span>
			</div>
			<div class="desc">I studied Biology at Hacettepe University. Attended conferences about Bioinformatics.<br>
			<center class="timelinegpa"><strong>GPA:3.30</strong></center> 
			</div>
		</div>
	</li>
	
	
	

</ul>
  
  

</body>

</html>
