---
layout: page
title: Portfolio
subtitle: Some Works From Us. 
---

<html lang="en" >

<head>
  <meta charset="UTF-8">
  <title>Bayveri's Timeline</title>	
</head>  

<style type="text/css" media="screen">



.thumbnail {
  max-width: 20%;
}

.italic { font-style: italic; }
.small { font-size: 0.8em; }

/** LIGHTBOX MARKUP **/

.lightbox {
	/** Default lightbox to hidden */
	display: none;

	/** Position and style */
	position: fixed;
	z-index: 999;
	width: 100%;
	height: 100%;
	text-align: center;
	top: 0;
	left: 0;
	background: rgba(0,0,0,0.8);
}

.lightbox img {
	/** Pad the lightbox image */
	max-width: 90%;
	max-height: 80%;
	margin-top: 8%;
}

.lightbox:target {
	/** Remove default browser outline */
	outline: none;

	/** Unhide lightbox **/
	display: block;
}

 </style>


<!-- thumbnail image wrapped in a link -->
<a href="#img1">
  <img src="http://insomnia.rest/images/screens/main.png" class="thumbnail">
</a>

<!-- lightbox container hidden with CSS -->
<a href="#_" class="lightbox" id="img1">
  <img src="http://insomnia.rest/images/screens/main.png">
</a>
	
</html>
