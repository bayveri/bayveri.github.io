---
layout: page
title: Publications
subtitle: Published Academic Works. 
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
 
              /*progress bar animated*/
 
 /* Load animation */
@-webkit-keyframes 
load { 0% {
stroke-dashoffset:0
}
}
@-moz-keyframes 
load { 0% {
stroke-dashoffset:0
}
}
@keyframes 
load { 0% {
stroke-dashoffset:0
}
}


.progress>li {
  display: inline-block;
  position: relative;
  text-align: center;
  color: #93A2AC;
  font-family: Lato;
  font-weight: 100;
  margin: 2rem;
}


.progress>li:before {
  content: attr(data-name);
  position: absolute;
  width: 100%;
  bottom: -2rem;
  font-weight: 400;
}

.progress>li:after {
  content: attr(data-percent);
  position: absolute;
  width: 100%;
  top: 3.7rem;
  left: 0;
  font-size: 2rem;
  text-align: center;
}

.progress svg {
  width: 10rem;
  height: 10rem;
}

.progress svg:nth-child(2) {
  position: absolute;
  left: 0;
  top: 0;
  transform: rotate(-90deg);
  -webkit-transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  -ms-transform: rotate(-90deg);
}

.progress svg:nth-child(2) path {
  fill: none;
  stroke-width: 25;
  stroke-dasharray: 629;
  stroke: rgba(255, 255, 255, 0.9);
  -webkit-animation: load 2s;
  -moz-animation: load 2s;
  -o-animation: load 2s;
  animation: load 2s;
}
 
 


 </style>

  
</head>

<body>

  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600,600italic,700,700italic' rel='stylesheet' type='text/css'>
  
<!-- The Timeline -->

<ul class="timeline">

	<!-- Item 1 -->
<li>
	<a href="https://verianaliz.net" style="margin: auto 60%" target="popup" rel="noopener noreferrer" onclick="window.open('https://www.verianaliz.net','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/coming.png"/></a>
	
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">Coming Soon</span>

				<span class="time-wrapper"><span class="time">2019</span></span>
	
			</div>
			<div class="desc"> <ul class="progress">
  <li data-name="Level" data-percent="100%"> <svg viewBox="-10 -10 220 220">
    <g fill="none" stroke-width="20" transform="translate(100,100)">
      <path d="M 0,-100 A 100,100 0 0,1 86.6,-50" stroke="url(#cl1)"/>
      <path d="M 86.6,-50 A 100,100 0 0,1 86.6,50" stroke="url(#cl2)"/>
      <path d="M 86.6,50 A 100,100 0 0,1 0,100" stroke="url(#cl3)"/>
      <path d="M 0,100 A 100,100 0 0,1 -86.6,50" stroke="url(#cl4)"/>
      <path d="M -86.6,50 A 100,100 0 0,1 -86.6,-50" stroke="url(#cl5)"/>
      <path d="M -86.6,-50 A 100,100 0 0,1 0,-100" stroke="url(#cl6)"/>
    </g>
    </svg> <svg viewBox="-10 -10 220 220">
    <path d="M200,100 C200,44.771525 155.228475,0 100,0 C44.771525,0 0,44.771525 0,100 C0,155.228475 44.771525,200 100,200 C155.228475,200 200,155.228475 200,100 Z" stroke-dashoffset="630"></path>
    </svg> </li>
</ul></div>
		</div>
	</li>
  
  
	<!-- Item 2 -->
	<li>
	
	<a href="https://verianaliz.net" style="margin: auto 20%" target="popup" rel="noopener noreferrer" onclick="window.open('https://verianaliz.net','popup','width=700,height=700'); return false;"><img class="timelineimage" src="/img/coming.png"/></a>
	<br>
		<div class="direction-l">
		
			<div class="flag-wrapper">
				<span class="flag">Coming Soon</span>
				
				<span class="time-wrapper"><span class="time">2019</span></span>
			</div>
			<div class="desc"> </div>
		</div>
	</li>
  

</ul>
  

<!--  Defining Angle Gradient Colors  --> 
<svg width="0" height="0">
<defs>
  <linearGradient id="cl1" gradientUnits="objectBoundingBox" x1="0" y1="0" x2="1" y2="1">
    <stop stop-color="#618099"/>
    <stop offset="100%" stop-color="#8e6677"/>
  </linearGradient>
  <linearGradient id="cl2" gradientUnits="objectBoundingBox" x1="0" y1="0" x2="0" y2="1">
    <stop stop-color="#8e6677"/>
    <stop offset="100%" stop-color="#9b5e67"/>
  </linearGradient>
  <linearGradient id="cl3" gradientUnits="objectBoundingBox" x1="1" y1="0" x2="0" y2="1">
    <stop stop-color="#9b5e67"/>
    <stop offset="100%" stop-color="#9c787a"/>
  </linearGradient>
  <linearGradient id="cl4" gradientUnits="objectBoundingBox" x1="1" y1="1" x2="0" y2="0">
    <stop stop-color="#9c787a"/>
    <stop offset="100%" stop-color="#817a94"/>
  </linearGradient>
  <linearGradient id="cl5" gradientUnits="objectBoundingBox" x1="0" y1="1" x2="0" y2="0">
    <stop stop-color="#817a94"/>
    <stop offset="100%" stop-color="#498a98"/>
  </linearGradient>
  <linearGradient id="cl6" gradientUnits="objectBoundingBox" x1="0" y1="1" x2="1" y2="0">
    <stop stop-color="#498a98"/>
    <stop offset="100%" stop-color="#618099"/>
  </linearGradient>
</defs>
</svg>



</body>

</html>
