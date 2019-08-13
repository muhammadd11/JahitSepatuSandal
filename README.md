
<!DOCTYPE html>
<html lang="id-ID" class="no-js">
	<head>
		<meta charset="UTF-8">
		<title>
			DB Desa Sumput
		</title>
		<link href="//www.google-analytics.com" rel="dns-prefetch">
				<link href="https://www.grab.com/id/wp-content/themes/grabsg/images/favicon.ico" rel="shortcut icon">
		<meta name="msvalidate.01" content="62D708192352CDCE3B73BA9B4A94A95C" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">

<script type='text/javascript' src='https://www.grab.com/sg/wp-content/uploads/media/js/secure-filters.js?ver=1.32110'></script>
		<!-- <meta name="description" content=""> -->

		<!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
		<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
		<!--[if lt IE 9]>
			<script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
			<script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
		<![endif]-->

		<!-- Google Optimize - Page Hiding Snippet-->
		<script>        (function (a, s, y, n, c, h, i, d, e) {
	            s.className += ' ' + y; h.start = 1 * new Date;
	            h.end = i = function () { s.className = s.className.replace(RegExp(' ?' + y), '') };
	            (a[n] = a[n] || []).hide = h; setTimeout(function () { i(); h.end = null }, c); h.timeout = c;
	        })(window, document.documentElement, 'async-hide', 'dataLayer', 4000,
	{ 'GTM-KSQQ83R': true });</script>
	    <!-- End of Google Optimize - Page Hiding Snippet -->
	    <!-- Google Optimize - Modified Analytics Tracking Code -->
	    <script>
	        (function (i, s, o, g, r, a, m) {
	            i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () {
	                (i[r].q = i[r].q || []).push(arguments)
	            }, i[r].l = 1 * new Date(); a = s.createElement(o),
	 m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)
	        })(window, document, 'script', 'https://www.google-analytics.com/analytics.js', 'ga');
	        ga('create', 'UA-73060858-1', 'auto');
	        ga('require', 'GTM-KSQQ83R');
	    </script>
	    <!-- End of Google Optimize - Modified Analytics Tracking Code -->
	    <!-- Google Tag Manager -->
	    <script>        (function (w, d, s, l, i) {
	            w[l] = w[l] || []; w[l].push({ 'gtm.start':
	new Date().getTime(), event: 'gtm.js'
	            }); var f = d.getElementsByTagName(s)[0],
	j = d.createElement(s), dl = l != 'dataLayer' ? '&l=' + l : ''; j.async = true; j.src =
	'https://www.googletagmanager.com/gtm.js?id=' + i + dl; f.parentNode.insertBefore(j, f);
	        })(window, document, 'script', 'dataLayer', 'GTM-54DG5SF');</script>
	    <!-- End Google Tag Manager -->

		<!-- Google Tag Manager -->
		<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
		new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
		j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
		'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
		})(window,document,'script','dataLayer','GTM-54DG5SF');</script>
		<!-- End Google Tag Manager -->

		<link rel="alternate" href="https://www.grab.com/th/" hreflang="th-th" />
<link rel="alternate" href="https://www.grab.com/th/en/" hreflang="en-th" />
<link rel="alternate" href="https://www.grab.com/vn/" hreflang="vi-vn" />
<link rel="alternate" href="https://www.grab.com/vn/en/" hreflang="en-vn" />
<link rel="alternate" href="https://www.grab.com/ph/" hreflang="en-ph" />
<link rel="alternate" href="https://www.grab.com/mm/" hreflang="my-mm" />
<link rel="alternate" href="https://www.grab.com/mm/en/" hreflang="en-mm" />
<link rel="alternate" href="https://www.grab.com/kh/" hreflang="en-kh" />
<link rel="alternate" href="https://www.grab.com/sg/" hreflang="en-sg" />
<link rel="alternate" href="https://www.grab.com/my/" hreflang="en-my" />
		<script>
		var stripHtml = (function () {
		  var div = document.createElement('div');
		  return function (html) {
		  	var escaped = secureFilters.html(html);
		  	return escaped;
		  	/*html = decodeURIComponent(html);
		  	console.log("HTML", html);
		    div.innerHTML = html.replace(/<\/?\w+[^>]*\/?>/g, "");
		    return (div.innerText || div.textContent); // textContent is for firefox*/
		  };
		})();
		//inject utm_source into cookies
		function getUrlParams() {
		    var rawQueryString = window.location.search;
		    if (!rawQueryString) {
		        return {};
		    }

		    rawQueryString = rawQueryString.slice(1);
		    var params = {};
		    var splitStrings = rawQueryString.split('&');

		    for (var i = 0, len = splitStrings.length; i < len; i++) {
		        var item = splitStrings[i].split('=');
		        params[item[0]] = stripHtml(decodeURIComponent(item[1]));
		        console.log(item[0], stripHtml(decodeURIComponent(item[1])));
		    }

		    return params;
		}

		function setCookie(name, value) {
		    document.cookie = name + "=" + value + "; max-age=86400; domain=.grab.com;path=/; secure";
		}

		var urlParams = getUrlParams();
		var searchEngines = {
		'www.google': 'Google',
		'search.yahoo': 'Yahoo',
		'www.bing': 'Bing',
		'baidu.com': 'Baidu',
		'm.baidu.com': 'Baidu'
		};
		var theReferrer = document.referrer;
		var referrerMatched;
		Object.keys(searchEngines).forEach(key => {
		if (theReferrer.includes(key)) {
			referrerMatched = searchEngines[key];
			return false;
		}
		});
		if (urlParams.utm_source) {
		setCookie('utm_source', urlParams.utm_source);
		} else if (referrerMatched) { setCookie('utm_source', referrerMatched);
		}
		if (urlParams.utm_medium) {
		setCookie('utm_medium', urlParams.utm_medium);
		} else if (referrerMatched) { setCookie('utm_medium', 'non-paid');
		}
		if (urlParams.utm_content) {setCookie('utm_content', urlParams.utm_content);}
		if (urlParams.utm_term) {setCookie('utm_term', urlParams.utm_term);}
		if (urlParams.utm_campaign) {setCookie('utm_campaign', urlParams.utm_campaign);}
		if (urlParams.grab_source) setCookie('grab_source', urlParams.grab_source);
		</script>

		<!-- Schema tag for JSON-LD structured data -->
					

		
				
<!-- Start The SEO Framework by Sybre Waaijer -->
<meta name="robots" content="noydir" />
<meta name="description" content="Satu applikasi untuk semua kebutuhan transportasi anda. Berbagai pilihan kendaraan kami sediakan untuk anda, dari mobil, ojek, dan taksi. Kami juga menyediakan jasa pengiriman barang dan makanan." />
<meta property="og:image" content="https://www.grab.com/id/wp-content/uploads/sites/9/2018/04/cropped-GC_FM_IMG_4200.jpg" />
<meta property="og:image:width" content="2000" />
<meta property="og:image:height" content="1052" />
<meta property="og:locale" content="id_ID" />
<meta property="og:type" content="website" />
<meta property="og:title" content="Grab, Decacorn Pertama di Asia Tenggara &#8211; Grab your Everyday Super App | Grab" />
<meta property="og:description" content="Satu applikasi untuk semua kebutuhan transportasi anda. Berbagai pilihan kendaraan kami sediakan untuk anda, dari mobil, ojek, dan taksi. Kami juga menyediakan jasa pengiriman barang dan makanan." />
<meta property="og:url" content="https://www.grab.com/id/" />
<meta property="og:site_name" content="Grab ID" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:site" content="@GrabID" />
<meta name="twitter:title" content="Grab, Decacorn Pertama di Asia Tenggara &#8211; Grab your Everyday Super App | Grab" />
<meta name="twitter:description" content="Satu applikasi untuk semua kebutuhan transportasi anda. Berbagai pilihan kendaraan kami sediakan untuk anda, dari mobil, ojek, dan taksi. Kami juga menyediakan jasa pengiriman barang dan makanan." />
<meta name="twitter:image" content="https://www.grab.com/id/wp-content/uploads/sites/9/2018/04/cropped-GC_FM_IMG_4200.jpg" />
<meta name="twitter:image:width" content="2000" />
<meta name="twitter:image:height" content="1052" />
<link rel="canonical" href="https://www.grab.com/id/" />
<script type="application/ld+json">{"@context":"http://schema.org","@type":"WebSite","url":"https://www.grab.com/id/","name":"Grab ID","alternateName":"Grab Indonesia","potentialAction":{"@type":"SearchAction","target":"https://www.grab.com/id/search/{search_term_string}","query-input":"required name=search_term_string"}}</script>
<script type="application/ld+json">{"@context":"http://schema.org","@type":"Organization","url":"https://www.grab.com/id/","name":"Grab Indonesia","sameAs":["https://www.facebook.com/GrabID/","https://twitter.com/grabid","https://www.instagram.com/grabid","https://www.youtube.com/channel/UCGW3n9AJpF31TS9hqC7FXdw","https://www.linkedin.com/company/grabapp"]}</script>
<meta name="google-site-verification" content="vfxuon_ZyPfaowDg8ecP-FSfSGVGrBY08WH0gISpyGk" />
<meta name="msvalidate.01" content="62D708192352CDCE3B73BA9B4A94A95C" />
<!-- End The SEO Framework by Sybre Waaijer | 0.00319s -->

<link rel='dns-prefetch' href='//cdnjs.cloudflare.com' />
<link rel='dns-prefetch' href='//s.w.org' />
		<script type="text/javascript">
			window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/11\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/11\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/www.grab.com\/id\/wp-includes\/js\/wp-emoji-release.min.js?ver=4.9.8"}};
			!function(a,b,c){function d(a,b){var c=String.fromCharCode;l.clearRect(0,0,k.width,k.height),l.fillText(c.apply(this,a),0,0);var d=k.toDataURL();l.clearRect(0,0,k.width,k.height),l.fillText(c.apply(this,b),0,0);var e=k.toDataURL();return d===e}function e(a){var b;if(!l||!l.fillText)return!1;switch(l.textBaseline="top",l.font="600 32px Arial",a){case"flag":return!(b=d([55356,56826,55356,56819],[55356,56826,8203,55356,56819]))&&(b=d([55356,57332,56128,56423,56128,56418,56128,56421,56128,56430,56128,56423,56128,56447],[55356,57332,8203,56128,56423,8203,56128,56418,8203,56128,56421,8203,56128,56430,8203,56128,56423,8203,56128,56447]),!b);case"emoji":return b=d([55358,56760,9792,65039],[55358,56760,8203,9792,65039]),!b}return!1}function f(a){var c=b.createElement("script");c.src=a,c.defer=c.type="text/javascript",b.getElementsByTagName("head")[0].appendChild(c)}var g,h,i,j,k=b.createElement("canvas"),l=k.getContext&&k.getContext("2d");for(j=Array("flag","emoji"),c.supports={everything:!0,everythingExceptFlag:!0},i=0;i<j.length;i++)c.supports[j[i]]=e(j[i]),c.supports.everything=c.supports.everything&&c.supports[j[i]],"flag"!==j[i]&&(c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&&c.supports[j[i]]);c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&&!c.supports.flag,c.DOMReady=!1,c.readyCallback=function(){c.DOMReady=!0},c.supports.everything||(h=function(){c.readyCallback()},b.addEventListener?(b.addEventListener("DOMContentLoaded",h,!1),a.addEventListener("load",h,!1)):(a.attachEvent("onload",h),b.attachEvent("onreadystatechange",function(){"complete"===b.readyState&&c.readyCallback()})),g=c.source||{},g.concatemoji?f(g.concatemoji):g.wpemoji&&g.twemoji&&(f(g.twemoji),f(g.wpemoji)))}(window,document,window._wpemojiSettings);
		</script>
		<style type="text/css">
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
<link rel='stylesheet' id='elementor/widgets/widgets_registered-css'  href='https://www.grab.com/id/wp-content/plugins/grab-elementor/assets/styles.css?ver=5217282' media='all' />
<link rel='stylesheet' id='bootstrap-css'  href='https://www.grab.com/id/wp-content/themes/grabsg/css/bootstrap.min.v3.3.6.css?ver=1.0' media='all' />
<link rel='stylesheet' id='common_css-css'  href='https://www.grab.com/id/wp-content/themes/grabsg/css/common.css?ver=20190702' media='' />
<link rel='stylesheet' id='press_css-css'  href='https://www.grab.com/id/wp-content/themes/grabsg/css/press-stylesheet.css?ver=20180124' media='' />
<link rel='stylesheet' id='sanomat_css-css'  href='https://www.grab.com/id/wp-content/themes/grabsg/fonts/Sanomat/1512-PNDUFW-11oct17.css?ver=20180124' media='' />
<link rel='stylesheet' id='tablepress-default-css'  href='https://www.grab.com/id/wp-content/plugins/tablepress/css/default.min.css?ver=1.9.1' media='all' />
<link rel='stylesheet' id='wpglobus-css'  href='https://www.grab.com/id/wp-content/plugins/wpglobus/includes/css/wpglobus.css?ver=1.9.16' media='all' />
<script type='text/javascript' src='https://www.grab.com/id/wp-includes/js/jquery/jquery.js?ver=1.12.4'></script>
<script type='text/javascript' src='https://www.grab.com/id/wp-includes/js/jquery/jquery-migrate.min.js?ver=1.4.1'></script>
<script type='text/javascript' src='https://www.grab.com/id/wp-content/plugins/elementor/assets/lib/swiper/swiper.jquery.min.js?ver=4.4.3'></script>
<script type='text/javascript' src='https://cdnjs.cloudflare.com/ajax/libs/Swiper/4.1.6/js/swiper.min.js?ver=147'></script>
<script type='text/javascript' src='https://www.grab.com/id/wp-content/plugins/grab-elementor/assets/scripts.js?ver=147'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var userSettings = {"url":"\/","uid":"0","time":"1565184810","secure":"1"};
/* ]]> */
</script>
<script type='text/javascript' src='https://www.grab.com/id/wp-includes/js/utils.min.js?ver=4.9.8'></script>
<link rel='https://api.w.org/' href='https://www.grab.com/id/wp-json/' />
<link rel="alternate" type="application/json+oembed" href="https://www.grab.com/id/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.grab.com%2Fid%2F" />
<link rel="alternate" type="text/xml+oembed" href="https://www.grab.com/id/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.grab.com%2Fid%2F&#038;format=xml" />
<style type="text/css">#section-raw-html-user-education-body header {display:none}

@media screen and (max-width: 767px){
  #section-carousel-homepage-carousel .carousel-inner .item:first-child{
    background-image:url("https://assets.grab.com/wp-content/uploads/sites/9/2018/10/15123807/grab_safety_headerimage_mobile.png")!important;
    background-position: right top !important;
  }
  
}

/* pop up maker starts
.pum-theme-lightbox .pum-container {
    border: 2px solid #00b14f;
    border-radius: 10px;
}
ul#input_40_3 {
    display: flex;
    margin: 10px;
}ul#input_40_3 label {
    padding-left: 8px;
     padding-right: 8px;
}
ul#input_40_1 li label{
    padding-left: 10px;
}
#input_40_1 li {
    margin-bottom: 3px;
    margin-top: 3px;
}
.gfield_description, .pum-title {
    margin-bottom: 10px;
    margin-top: 10px;
}
.pum-theme-lightbox .pum-content + .pum-close {
    right: -10px;
    top: -15px;
}
#survey-blue-bar {
  position: fixed;
  bottom: 0;
  right: 0;
  padding: .5em 1em;
  border-top-left-radius: .5em;
  border-bottom-left-radius: .5em;
  color: white;
  background: #00A5CF;
  box-shadow: -.1em -.3em 1em .1em rgba(0,0,0,.15);
  z-index: 999;
}

#survey-blue-bar a {
  color: white;
  text-decoration: none;
}

#survey-blue-bar .close-blue-bar {
  margin-left: .5em;
  font-size: 2em;
  vertical-align: middle;
}
/* pop up maker ends */</style><script type="text/javascript">
           var ajaxurl = "https://www.grab.com/id/wp-admin/admin-ajax.php";
         </script>			<style type="text/css" media="screen">
				.wpglobus_flag_id{background-image:url(https://www.grab.com/id/wp-content/plugins/wpglobus/flags/id.png)}
.wpglobus_flag_en{background-image:url(https://www.grab.com/id/wp-content/plugins/wpglobus/flags/us.png)}
                                    			</style>
							* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
				</head>
	<body class="home page-template page-template-tpl page-template-tpl-page-sections page-template-tpltpl-page-sections-php page page-id-285 site-id-9 elementor-default">
		<!-- Google Tag Manager (noscript) -->
		<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-54DG5SF"
		height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
		<!-- End Google Tag Manager (noscript) -->

				
		
		
		
		

		<div id="top">
			<div class="container">

<!-- new menu -->
<!-- end of new menu -->


					<div class="navbar-header">
						<!-- ktmu -->
					</div>
					<!-- end -->
									<p class= "flag" style="text-align: center;"> JAHIT SOL SEPATU-SANDAL </p> 
																		
					

															<ul id="nav-drive" class="nav navbar-nav navbar-right hidden-xs ">
						<li class="dropdown">
							<a href="https://bitly.li/rQ5Ro" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
								PESAN DISINI							</a>
							<ul class="dropdown-menu list-icons">
														
								<li class="abc" style="">
									<a href="https://bitly.li/rQ5Ro" class="icon-drive-white" style="">
									KLIK</a>
								</li>
													
					</ul>
					!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 2</div>
    <img src="Sepatu-trainer-black.jpg" style="width:100%">
     <div class="carousel-caption">
									                <h1>Untuk Indonesia yang lebih percaya diri</h1>
													<p></p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="https://bitly.li/rQ5Ro">PESAN DISINI</a>	
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 2</div>
    <img src="set-various-male-female-shoes_74855-194.jpg" style="width:100%">
     <div class="carousel-caption">
									                <h1>Untuk Indonesia yang lebih percaya diri</h1>
													<p></p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="https://bitly.li/rQ5Ro">PESAN DISINI</a>	
  </div>

  
  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
</div>
				
				var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1} 
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none"; 
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block"; 
  dots[slideIndex-1].className += " active";
}

				
							
														
														
														
														
							
							
														
				
									
											
												
														
							
														
														
														
							
					
														
														
														
														
														
															
