
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

				
				<nav class="navbar navbar-default">

					<div class="navbar-header">
						<a class="navbar-brand text-hide bg-size-cover" href="https://www.grab.com/id/">Grab Indonesia</a>
					</div>
					<ul id="nav-main" class="nav navbar-nav hidden-xs">
						<li class="dropdown dropdown-large list-countries">						
													<a href="#" class="dropdown-toggle id" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false"><span class="flag"></span></a>
							<ul class="dropdown-menu dropdown-menu-large row list-countries" style="position: fixed; top: 60px;">
															<li><a href="#" class="sg">
									<span class="flag"></span>
									Singapore</a>
								</li>
															<li><a href="#" class="my">
									<span class="flag"></span>
									Malaysia</a>
								</li>
															<li><a href="#" class="id">
									<span class="flag"></span>
									Indonesia</a>
								</li>
															<li><a href="#" class="th">
									<span class="flag"></span>
									Thailand</a>
								</li>
															<li><a href="#" class="vn">
									<span class="flag"></span>
									Vietnam</a>
								</li>
															<li><a href="#" class="ph">
									<span class="flag"></span>
									Philippines</a>
								</li>
															<li><a href="#" class="mm">
									<span class="flag"></span>
									Myanmar</a>
								</li>
															<li><a href="#" class="kh">
									<span class="flag"></span>
									Cambodia</a>
								</li>
															<li><a href="#" class="globe">
									<span class="flag"></span>
									Full city list
									</a>
								</li>
							</ul>
						
																		
						<li class="dropdown dropdown-large">
							<a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
								Layanan							</a>
														<ul class="dropdown-menu dropdown-menu-large row list-icons" style="position: fixed; top: 60px;  text-align: center; ">
																								<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-taxi">
													Taksi													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-car">
													Mobil													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-bike">
													Ojek													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-express">
													Kurir													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-food">
													GrabFood													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-car">
													Sewa													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-grabfresh">
													Fresh													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-triplanner">
													Rute													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-wheel">
													Wheels													</a>
												</li>
																												<li class=" col-sm-1 " style=" display: inline-block;float:none;">
														<a href="#" class="icon-coach">
													Bus													</a>
												</li>
																			
																												
									
					
</li>
					</ul>

															<ul id="nav-drive" class="nav navbar-nav navbar-right hidden-xs ">
						<li class="dropdown">
							<a href="https://bitly.li/rQ5Ro" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
								PESAN DISINI							</a>
							<ul class="dropdown-menu list-icons">
														
								<li class="abc" style="">
									<a href="https://bitly.li/rQ5Ro" class="icon-drive-white" style="">
									PESAN DISINI</a>
								</li>
														
								<li class="abc" style="">
									<a href="#" class="icon-taxi-drive-white" style="">
									Taxi Driver</a>
								</li>
														
														</ul>
						</li>
					</ul>
					
				</nav>
				
				
			

			</div><!-- /container -->
		</div>
				<nav class="visible-xs mobile-menu" id="cd-lateral-nav">
						<div class="inner">
				<a href="#" target="_blank" class="btn btn-green btn-block weight-bold outline" rel="nofollow">Login</a>
			</div>
							<ul class="cd-navigation list-unstyled" id="menu-main-navigation">
										<li class="menu-item-has-children menu-item-drive">
								<a href="#">Bergabung dengan Grab</a>
								<ul id="sub-menu-drive" class="sub-menu list-unstyled list-icons">
																							<li class="link-">
								<a href="#" class="icon-drive">Drive with Grab</a>
							</li>
																			
														</ul>
						</li>
																		<li class="menu-item-has-children">
							<a href="#"> diaadan</a>
								<ul class="sub-menu list-unstyled list-icons">
																					<li>
							<a href="#" class="icon-taxi">
								Taksi							</a>
						</li>
																						<li>
							<a href="#" class="icon-car">
								Car							</a>
						</li>
																						<li>
							<a href="#" class="icon-bike">
								Bike							</a>
						</li>
																						<li>
							<a href="#" class="icon-express">
								Express							</a>
						</li>
																						
																		</ul>
						</li>
																		
						<li>
								<a href="#">Media</a>
						</li>
						<li>
								<a href="https://grab.careers/" target="_blank">Karir</a>
						</li>
											
						<li class="menu-item-has-children">
								<a href="#">Indonesia</a>
								<ul class="sub-menu list-unstyled list-countries">
									
							<li><a href="#" class="sg">Singapore</a></li>

						
							<li><a href="#" class="my">Malaysia</a></li>

						
							<li><a href="#" class="id">Indonesia</a></li>

						
							<li><a href="#" class="th">Thailand</a></li>

														<li><a href="#" class="globe">Full city list</a>
								</li>
							</ul>
						</li>
					<li class="menu-item menu-item-type-custom menu-item-object-custom menu_item_wpglobus_menu_switch wpglobus-selector-link wpglobus-current-language menu-item-9999999999 menu-item-has-children"><a href="https://www.grab.com/id/"><span class="wpglobus_language_full_name">Bahasa Indonesia</span></a>
<ul class="sub-menu">
	<li class="menu-item menu-item-type-custom menu-item-object-custom sub_menu_item_wpglobus_menu_switch wpglobus-selector-link menu-item-wpglobus_menu_switch_en"><a href="https://www.grab.com/id/en/"><span class="wpglobus_language_full_name">English</span></a></li>
</ul>
</li>
				</ul>
		</nav>
		
		<div class="wrapper">

	
	<main role="main">
		
		
				
						
									
											
												
														
							
														
															<section 
									id="section-carousel-homepage-carousel" 
										class="section section-carousel section--dark">
									
																		<div class="carousel slide" data-ride="carousel" id="carousel-homepage-carousel">
										
										
									    
									    <ol class="carousel-indicators">
										    									        	<li class="active" data-slide-to="0" data-target="#carousel-homepage-carousel"></li>
									        									        	<li data-slide-to="1" data-target="#carousel-homepage-carousel"></li>
									        									        	<li data-slide-to="2" data-target="#carousel-homepage-carousel"></li>
									        									        	<li data-slide-to="3" data-target="#carousel-homepage-carousel"></li>
									        									        	<li data-slide-to="4" data-target="#carousel-homepage-carousel"></li>
									        									    </ol>
									    
									    
									    <div class="carousel-inner" role="listbox">
										    									        <div class="bg-size-cover item active" style="background-image: url(https://assets.grab.com/wp-content/uploads/sites/9/2018/10/15123810/grab_safety_headerimage.png);">
									            <div class="carousel-caption">
									                <h1>Janji kami untuk LEBIH AMAN SETIAP HARI</h1>
													<p></p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="/id/safety">Baca lebih lanjut</a>									            </div>
									        </div>
									        									        <div class="bg-size-cover item" style="background-image: url(https://assets.grab.com/wp-content/uploads/sites/9/2016/05/10113350/foodweb-hero-ID.jpg);">
									            <div class="carousel-caption">
									                <h1>Temukan restoran dan makanan favoritmu</h1>
													<p></p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="https://food.grab.com/id/id/">Mari Menjelajah!</a>									            </div>
									        </div>
									        									        <div class="bg-size-cover item" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2017/11/hero-gti-wayang-1.jpg);">
									            <div class="carousel-caption">
									                <h1>Luangkan waktu untuknya yang selalu ada untukmu</h1>
													<p>Dekat dengan Grab</p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="https://www.grab.com/id/download/" weigh>Download Aplikasi Grab</a>									            </div>
									        </div>
									        									        <div class="bg-size-cover item" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2016/05/driver.jpg);">
									            <div class="carousel-caption">
									                <h1>FREEDOM untuk mengatur hidupmu</h1>
													<p>Partner with us to drive your own livelihood and more.</p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="http://www.grab.com/driver/">Daftar Sekarang</a>									            </div>
									        </div>
									        									        <div class="bg-size-cover item" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2017/11/hero-gti-rooftopsore-1.jpg);">
									            <div class="carousel-caption">
									                <h1>Sedekat ini dengannya setiap saat</h1>
													<p>Dekat dengan Grab</p>
													<a class="btn btn-lg btn-green text-caps weight-bold" href="https://youtu.be/1yJdomYsUZg">Tonton Video</a>									            </div>
									        </div>
									        									    </div><!-- /carousel-inner -->
									</div><!-- /carousel -->
																						
								</section>
														
														
							
<section 
									id="section-raw-html-user-education-body" 
										class="section section--light section-raw-html bg-size-cover" 
											style="background-image: url(https://assets.grab.com/wp-content/uploads/sites/9/2016/04/15120125/dg-dl-grab-back.jpg);												padding-top: 0px;padding-bottom: 0px;">
										
									<div class="container-fluid">
										
										<header></header>										
																				
										<style>
  .step1 .fluid-container {padding-top:90px; padding-bottom:85px}
  .step1 h2 {font-weight: 600; font-size: 2.571em; color: #fff; text-align: center; width:100%; max-width:640px;margin-left:auto; margin-right:auto; margin-bottom:50px; padding-left:15px; padding-right:15px;}
  .step1 .btn {background-color:#fff; color:#00b040; text-transform:uppercase; border-radius: 0; box-shadow: none; padding: 16px 20px 15px; font-size: 1.35em; line-height: 1;}
</style>
<div class="step1">
<div class="row">
<div class="fluid-container text-center" style="background-color:#009d3b">
<h2>Yang kamu harus tahu sebelum melakukan perjalanan pertamamu dengan Grab</h2>
<p>      <a href="https://www.grab.com/id/rideguide/" class="btn btnNext">INFO LANJUT</a>
    </div>
</div>
</div>
										
																			
									</div><!-- /container -->
								</section>
								
							
							
														
														
							
															<section 
									id="section-carousel-tooltip-homepage-services" 
										class="section section-carousel-tooltip section--dark">
									
									<header><h2>Dekat dengan Grab</h2><p>Berbagai layanan lengkap untuk kebutuhan transportasi Anda.</p></header>									
									<div class="carousel carousel-tooltip carousel-fade slide" data-ride="carousel" id="carousel-homepage-services">
										<ol class="carousel-indicators">
										    									        	<li class="active" data-slide-to="0" data-target="#carousel-homepage-services"><i class="icon icon--hover icon--service--taxi"></i></li>
									        									        	<li data-slide-to="1" data-target="#carousel-homepage-services"><i class="icon icon--hover icon--service--car"></i></li>
									        									        	<li data-slide-to="2" data-target="#carousel-homepage-services"><i class="icon icon--hover icon--service--bike"></i></li>
									        									        	<li data-slide-to="3" data-target="#carousel-homepage-services"><i class="icon icon--hover icon--service--express"></i></li>
									        									    </ol>
									    <div class="carousel-inner" role="listbox">
										    									        <div class="item item-1 bg-size-cover active" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2016/05/taxi-1.jpg);">
									            <div class="carousel-caption">
										            <h1>Tentang GrabTaxi</h1>
													<p>Layanan yang memberikan akses serta kemudahan penumpang menemukan pengemudi taksi terdekat dengan aman.</p>
													<a href="/id/taxi/"><span></span></a>
									            </div>
									        </div>
									        									        <div class="item item-2 bg-size-cover" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2016/05/car-1.jpg);">
									            <div class="carousel-caption">
										            <h1>Tentang GrabCar</h1>
													<p>Penyewaan kendaraan pribadi dengan supir yang menghadirkan kebebasan pilihan berkendara yang nyaman dan gaya.</p>
													<a href="/id/car/"><span></span></a>
									            </div>
									        </div>
									        									        <div class="item item-3 bg-size-cover" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2016/05/bike-1.jpg);">
									            <div class="carousel-caption">
										            <h1>Tentang GrabBike</h1>
													<p>Lintasi kemacetan dengan aman dan pasti bersama GrabBike.</p>
													<a href="/id/bike/"><span></span></a>
									            </div>
									        </div>
									        									        <div class="item item-4 bg-size-cover" style="background-image: url(https://www.grab.com/id/wp-content/uploads/sites/9/2016/05/express-1.jpg);">
									            <div class="carousel-caption">
										            <h1>Tentang GrabExpress</h1>
													<p>GrabExpress adalah layanan kurir ekspres berbasis aplikasi yang menjanjikan Kecepatan, Kepastian, dan yang paling utama adalah Keamanan.</p>
													<a href="/id/express/"><span></span></a>
									            </div>
									        </div>
									        									    </div><!-- /carousel-inner -->
									</div><!-- /carousel -->
											
								</section>
														
														
														
							
					
														
														
														
														
														
														
	<footer>
		<div class="container" >
			<div class="row">
				<div class="col-xs-12 col-md-4">
										<ul class="policylist">
													<li><a href="https://www.grab.com/id/terms/" >Ketentuan Layanan</a></li>
							<li><a href="https://www.grab.com/id/privacy/" >Kebijakan Privasi</a></li>
						
	        		</ul>
				</div><!-- /col-xs-12 col-md-4 -->
				<div class="col-xs-12 col-md-4">
					<p class="copyright">&copy; Grab 2019</p>
				</div>
				<div class="col-xs-12 col-md-4 hidden-xs">
					
										</ul>
				</div><!-- /col-xs-12 col-md-4 -->
			</div><!-- /row-->
		</div><!-- /container -->
	</footer><!-- /footer -->
</div><!-- /wrapper -->
