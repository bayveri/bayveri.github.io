---
layout: page
title: Timeline
subtitle: From the latest to earlier you can scrool down and learn more about me.
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
  font-size: 130%;
  line-height: 1.6em;
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
  font-size: 0.66666em;
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
  
  font-size: 1em;
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
 
 </style>

  
</head>

<body>

  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600,600italic,700,700italic' rel='stylesheet' type='text/css'>
  
<!-- The Timeline -->

<ul class="timeline">

	<!-- Item 1 -->
<li>
	
	<a href="https://verianaliz.net" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/verianaliz.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">VeriAnaliz.net - Founder</span>
				
				
				
				<span class="time-wrapper"><span class="time">2019 - present</span></span>
				
				
				
			</div>
			<div class="desc">My current employment. Way better than the position before!</div>
		</div>
	</li>
  
	<!-- Item 2 -->
	<li>
	
	<a href="http://www.egefinansdernegi.org/" style="margin: auto 30%" target="popup" rel="noopener noreferrer" onclick="window.open('http://www.egefinansdernegi.org/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/efd.png"/></a>
	
		<div class="direction-l">
		
			<div class="flag-wrapper">
				<span class="flag">EFD - IT Consultant</span>
				
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc"> EFD stands for Aegean Finance Association. I am consulting web development, web design, graphic design, and data analytics processes of the association.</div>
		</div>
	</li>
  
	<!-- Item 3 -->
	<li>
	
	<a href="https://ege.edu.tr/tr-0/anasayfa.html" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://ege.edu.tr/tr-0/anasayfa.html','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/ege.png"/></a>
		<div class="direction-r">
		
			<div class="flag-wrapper">
				<span class="flag">Ege University - Scholar </span>
				<span class="time-wrapper"><span class="time">2018 - present</span></span>
			</div>
			<div class="desc">I am a PhD Candidate in Economics. I am awarded scholarship on Multidisciplinary studies by Ege University. I work part-time as Research Asistant , Web Developer and Data Analyst.</div>
		</div>
	</li>

		<!-- Item 4 -->
	<li>
	  
	  <a href="https://www.tubitak.gov.tr/" style="margin: auto 30%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.tubitak.gov.tr/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/tübitak.png"/></a>
	  <br>	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">TÜBİTAK - Data Analyst</span>
				<span class="time-wrapper"><span class="time">2017 - 2018</span></span>
			</div>
			<div class="desc">TÜBİTAK is The Scientific and Technological Research Council of Turkey. I was part of a research project related to competitiveness of the companies in Turkey funded by the council.  I used and improved my big data analytics skills that was building along with my latest finance job and personal interest.</div>
		</div>
	</li>
 
		<!-- Item 5 -->
	<li>
	
	<a href="http://www.roca.com/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('http://www.roca.com/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/roca.png"/></a>
	
		<div class="direction-r"
		
			<div class="flag-wrapper">
				<span class="flag">Roca Sanitario - Finance Asistant</span>
				<span class="time-wrapper"><span class="time">2017 - 2018</span></span>
			</div>
			<div class="desc">I was responsible for and part of whole finance process of an international production Company. Those includes: bookkeeping, observing value chain of the Company, derive reports using adhoc cost accounting methods,  bridging manually between Turkish accounting system and Spanish IFRS, reporting monthly financial position of the company to the manager and Headquarter, reporting required information to the Turkish Institutions such as Central Bank and TÜİK.</div>
		</div>
	</li>
	
			<!-- Item 6 -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 30%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en'); return false;"><img class="timelineimage" src="/img/anadolu.png"/></a>
	<br>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">Anadolu University</span>
				<span class="time-wrapper"><span class="time">2016 - 2018</span></span>
			</div>
			<div class="desc">I started my PhD in Economics at Anadolu University. At this time, I took classes related to Data Analytics from Department of Computer Engineering. I continue my academic career at Ege University as I have beed awarded scholarship.</div>
		</div>
	</li>
	
			<!-- Item 7 -->
	<li>
	
	<a href="https://www.atilim.edu.tr/tr" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.atilim.edu.tr/tr','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/atılım.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">Atılım University</span>
				<span class="time-wrapper"><span class="time">2015 - 2016</span></span>
			</div>
			<div class="desc">I took advanced English courses with a full scholarship for one year.</div>
		</div>
	</li>
	
				<!-- Item 8 -->
	<li>
	
	<a href="https://www.anadolu.edu.tr/en" style="margin: auto 30%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.anadolu.edu.tr/en','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/anadolu.png"/></a>
	<br>
	
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">Anadolu Univiversity - H.B.Econ.</span>
				<span class="time-wrapper"><span class="time">2011 - 2015</span></span>
			</div>
			<div class="desc"> I started studying Economics second year of my ongoing education in Biology. After the gap year, I took at the beginning of the university, I have already started reading on Economics. I have studied both subject at the same time and I granted honor degree both of them.<br>
			<center class="timelinegpa"><strong>GPA:3.55</strong></center></div>
		</div>
	</li>
	
				<!-- Item 9 -->
	<li>
	<a href="https://www.hacettepe.edu.tr/english/" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.hacettepe.edu.tr/english/','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/hacettepe.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">Hacettepe University - Hons.B.Sc.</span>
				<span class="time-wrapper"><span class="time">2009 - 2015</span></span>
			</div>
			<div class="desc">I studied Biology. Established Biotechnology Research Student Club with friends. Graduated with first class honour degree (as being a Biologist, have fulfilled my childhood dream). At the same time majored in Economics from Anadolu University.<br>
			<center class="timelinegpa"><strong>GPA:3.30</strong></center> 
			</div>
		</div>
	</li>
	
</ul>
  
  

</body>

</html>
