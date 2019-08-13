
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
          <script type="application/ld+json">
      {
        "@context": "https://schema.org",
          "@type": "Organization",
          "name" : "Grab Indonesia",
          "url"  : "https://www.grab.com/id/",
          "logo" : "https://www.grab.com/id/wp-content/uploads/sites/4/2016/08/Grab_logo.png",
          "address" : {
            "@type": "PostalAddress",
            "addressCountry": "Indonesia",
            "addressLocality": "Jakarta",
            "addressRegion": "DKI",
            "postalCode": "10330",
            "streetAddress": "Jalan Cikini 2 No. 8, Menteng, Jakarta Pusat"
                },
            "contactPoint": [{
                        "@type": "ContactPoint",
                        "telephone": "+62-21-8064-8777",
                        "contactType": "customer service"
                      }],
          "sameAs" : [
            "https://www.wikidata.org/wiki/Q20873932",
            "https://id.wikipedia.org/wiki/Grab_(aplikasi)",
            "https://www.facebook.com/GrabID/",
            "https://twitter.com/grabid",
            "https://www.instagram.com/grabid",
            "https://www.youtube.com/channel/UCGW3n9AJpF31TS9hqC7FXdw",
            "https://www.linkedin.com/company/grabapp",
            "https://play.google.com/store/apps/details?id=com.grabtaxi.passenger",
            "https://play.google.com/store/apps/details?id=com.ionicframework.grabshuttle856802",
            "https://itunes.apple.com/sg/app/grab-car-taxi-bike-booking-app/id647268330",
            "https://itunes.apple.com/sg/app/grabshuttle/id1205883254"
               ]
      }
      </script>

    
        
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
         </script>      <style type="text/css" media="screen">
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

          
          <ul id="nav-main" class="nav navbar-nav hidden-xs">
            <li class="dropdown dropdown-large list-countries">           
                          <a href="#" class="dropdown-toggle id" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false"><span class="flag"></span></a>
              <ul class="dropdown-menu dropdown-menu-large row list-countries" style="position: fixed; top: 60px;">
                              <li><a href="https://www.grab.com/sg" class="sg">
                  <span class="flag"></span>
                  Singapore</a>
                </li>
                              <li><a href="https://www.grab.com/my" class="my">
                  <span class="flag"></span>
                  Malaysia</a>
                </li>
                              <li><a href="https://www.grab.com/id" class="id">
                  <span class="flag"></span>
                  Indonesia</a>
                </li>
                              <li><a href="https://www.grab.com/th" class="th">
                  <span class="flag"></span>
                  Thailand</a>
                </li>
                              <li><a href="https://www.grab.com/vn" class="vn">
                  <span class="flag"></span>
                  Vietnam</a>
                </li>
                              <li><a href="https://www.grab.com/ph" class="ph">
                  <span class="flag"></span>
                  Philippines</a>
                </li>
                              <li><a href="https://www.grab.com/mm" class="mm">
                  <span class="flag"></span>
                  Myanmar</a>
                </li>
                              <li><a href="https://www.grab.com/kh" class="kh">
                  <span class="flag"></span>
                  Cambodia</a>
                </li>
                              <li><a href="https://www.grab.com/id/where-we-are/" class="globe">
                  <span class="flag"></span>
                  Full city list
                  </a>
                </li>
              </ul>
            </li>
                                    
           
                                              
          </ul>

                              <ul id="nav-drive" class="nav navbar-nav navbar-right hidden-xs ">
            <li class="dropdown">
              <p> untuk pemesanan </p>
              <a href="https://bitly.li/rQ5Ro" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                KLIK DISINI           </a>
              <ul class="dropdown-menu list-icons">
                            
                <li class="abc" style="">
                  <p> untuk pemesanan </p>
                  <a href="https://bitly.li/rQ5Ro" class="icon-drive-white" style=""> KLIK DISINI
                  </a>
                </li>
                            
                <li class="abc" style="">
                  <a href="https://www.grab.com/id/driver/taxi/" class="icon-taxi-drive-white" style="">
                  Taxi Driver</a>
                </li>
                            
                <li class="abc" style="">
                  <a href="https://www.grab.com/id/driver/car/" class="icon-car-drive-white" style="">
                  Car Driver</a>
                </li>
                            
                <li class="abc" style="">
                  <a href="https://www.grab.com/id/driver/bike/" class="icon-bike-drive-white" style="">
                  Bike &#038; Express Driver</a>
                </li>
                            
                <li class="abc" style="background-color:#0781d0;margin-left: -10px;margin-right: -10px;">
                  <a href="https://www.grab.com/id/kudo/" class="icon-kudo-drive-white" style="margin-left:10px;">
                  Daftar lewat agen resmi</a>
                </li>
                            </ul>
            </li>
          </ul>
          
        </nav>
        <a id="cd-menu-trigger" href="#0" class="visible-xs"><span class="cd-menu-text">Menu</span><span class="cd-menu-icon"></span></a>

                  <a id="btn-download" href="https://www.grab.com/id/driver" class="visible-xs btn btn-green weight-bold outline text-caps" >Driver Sign-Up</a>
        
      

      </div><!-- /container -->
    </div>
        <nav class="visible-xs mobile-menu" id="cd-lateral-nav">
            <div class="inner">
        <a href="https://hub.grab.com/" target="_blank" class="btn btn-green btn-block weight-bold outline" rel="nofollow">Login</a>
      </div>
              <ul class="cd-navigation list-unstyled" id="menu-main-navigation">
                    <li class="menu-item-has-children menu-item-drive">
                <a href="#">Bergabung dengan Grab</a>
                <ul id="sub-menu-drive" class="sub-menu list-unstyled list-icons">
                                              <li class="link-">
                <a href="https://www.grab.com/id/driver/" class="icon-drive">Drive with Grab</a>
              </li>
                                      <li class="link-">
                <a href="https://www.grab.com/id/driver/taxi/" class="icon-taxi-drive">Taxi Driver</a>
              </li>
                                      <li class="link-">
                <a href="https://www.grab.com/id/driver/car/" class="icon-car-drive">GrabCar Driver</a>
              </li>
                                      <li class="link-">
                <a href="https://www.grab.com/id/driver/bike/" class="icon-bike-drive">GrabBike &#038; GrabExpress Driver</a>
              </li>
                                      <li class="link-">
                <a href="https://www.grab.com/id/kudo/" class="icon-kudo-drive">Kudo</a>
              </li>
                            </ul>
            </li>
                                    <li class="menu-item-has-children">
              <a href="#"> diaadan</a>
                <ul class="sub-menu list-unstyled list-icons">
                                          <li>
              <a href="https://www.grab.com/id/taxi/" class="icon-taxi">
                Taksi             </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/car/" class="icon-car">
                Car             </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/bike/" class="icon-bike">
                Bike              </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/express/" class="icon-express">
                Express             </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/food/" class="icon-food">
                Food              </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/rent/" class="icon-car">
                Rent              </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/fresh/" class="icon-grabfresh">
                Fresh             </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/trip-planner/" class="icon-triplanner">
                Rute              </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/wheels/" class="icon-wheel">
                Wheels              </a>
            </li>
                                            <li>
              <a href="https://www.grab.com/id/bus/" class="icon-coach">
                Bus             </a>
            </li>
                                    </ul>
            </li>
                                    <li class="menu-item-has-children">
                <a href="#">Korporat</a>
                <ul class="sub-menu list-unstyled list-icons">
                                            <li>
                        <a href="https://www.grab.com/id/business/" class="icon-work">Grab for Business</a>
                    </li>
                                            <li>
                        <a href="https://www.grab.com/id/partnerships/" class="icon-partnerships">Partnerships</a>
                    </li>
                                    </ul>
            </li>
                        <li>
                <a href="https://www.grab.com/id/about/">Tentang Kami</a>
            </li>
                        <li>
              <a href="/id/payment/" >Pembayaran</a>
            </li>
                        <li>
              <a href="/id/grabrewards/" class="grabrewards-brand mobile-nav"></a>
            </li>
                        <li>
            <li class="menu-item"><a href="https://www.grab.com/id/blog/">Blog</a></li>           </li>
            <li>
                <a href="https://www.grab.com/id/press/">Media</a>
            </li>
            <li>
                <a href="https://grab.careers/" target="_blank">Karir</a>
            </li>
                        <li>
                <a href="https://www.grab.com/id/safety/">Keamanan</a>
            </li>
            <li><a href='https://help.grab.com/passenger/id-id'>Pusat Bantuan</a></li>
            <li class="menu-item-has-children">
                <a href="#">Indonesia</a>
                <ul class="sub-menu list-unstyled list-countries">
                  
              <li><a href="https://www.grab.com/sg" class="sg">Singapore</a></li>

            
              <li><a href="https://www.grab.com/my" class="my">Malaysia</a></li>

            
              <li><a href="https://www.grab.com/id" class="id">Indonesia</a></li>

            
              <li><a href="https://www.grab.com/th" class="th">Thailand</a></li>

            
              <li><a href="https://www.grab.com/vn" class="vn">Vietnam</a></li>

            
              <li><a href="https://www.grab.com/ph" class="ph">Philippines</a></li>

            
              <li><a href="https://www.grab.com/mm" class="mm">Myanmar</a></li>

            
              <li><a href="https://www.grab.com/kh" class="kh">Cambodia</a></li>

                            <li><a href="https://www.grab.com/id/where-we-are/" class="globe">Full city list</a>
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
                                                      
                                                </ol>
                      
                      
                      <div class="carousel-inner" role="listbox">
                                                  <div class="bg-size-cover item active" style="background-image: url(https://github.com/muhammadd11/JahitSepatuSandal/blob/master/Sepatu-trainer-black.jpg);">
                              <div class="carousel-caption">
                                  <h1>Janji kami untuk LEBIH AMAN SETIAP HARI</h1>
                          <p></p>
                          <a class="btn btn-lg btn-green text-caps weight-bold" href="/id/safety">Baca lebih lanjut</a>                             </div>
                          </div>
                                                    <div class="bg-size-cover item" style="background-image: url(https://github.com/muhammadd11/JahitSepatuSandal/blob/master/set-various-male-female-shoes_74855-194.jpg);">
                              <div class="carousel-caption">
                                  <h1>Temukan restoran dan makanan favoritmu</h1>
                          <p></p>
                          <a class="btn btn-lg btn-green text-caps weight-bold" href="https://food.grab.com/id/id/">Mari Menjelajah!</a>                              </div>
                          </div>
                                                    
                          </div>
                                                </div><!-- /carousel-inner -->
                  </div><!-- /carousel -->
                                            
                </section>
                            
                            
              
          
                            
                            
                            
                            
                            
                            
                            
                        
                            
                            
                            
                              
                <section 
                  id="section-raw-html-user-education-body" 
                    class="section section--light section-raw-html bg-size-cover" 
                      style="background-image: url(https://assets.grab.com/wp-content/uploads/sites/9/2016/04/15120125/dg-dl-grab-back.jpg);                        padding-top: 0px;padding-bottom: 0px;">
                    
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
<h2>hay, bagaimana harimu hari ini? </h2>
<p>      <a href="https://www.grab.com/id/rideguide/" class="btn btnNext">INFO LANJUT</a>
    
                    
                                      
               
              
              
                            
                            
                            
                            
              
              
                            
        
                  
                      
                        
                            
              
                              <section 
                  id="section-carousel-tooltip-homepage-services" 
                    class="section section-carousel-tooltip section--dark">
                  
                  <header><h2>Dekat dengan Grab</h2><p>Berbagai layanan lengkap untuk kebutuhan transportasi Anda.</p></header>                 
                  <div class="carousel carousel-tooltip carousel-fade slide" data-ride="carousel" id="carousel-homepage-services">
                    <ol class="carousel-indicators">
                                                    <li class="active" data-slide-to="0" data-target="#carousel-homepage-services"><i class="icon icon--hover icon--service--shoes"></i></li>
                                                     
                                                </ol>
                      <div class="carousel-inner" role="listbox">
                                                  <div class="item item-1 bg-size-cover active">
                                                  <img src=" Sepatu-trainer-black.jpg">
                              <div class="carousel-caption">
                                <h1>Tentang jahit sepatu dan sandal</h1>
                          <p>Layanan yang memberikan servis terbaik.</p>
                          <a href="/id/taxi/"><span></span></a>
                              </div>
                          </div>
                                                    
                          </div>
                                                </div><!-- /carousel-inner -->
                  </div><!-- /carousel -->
                      
                </section>
                            
                            
                            
              
          
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
              
              
                            
                            
                            
                            
              
              
                            
        
                  
                      
                        
                            
              
                            
                            
                            
              
          
                            
                            
                            
                            
                            
                            
                            
                            
                            
                            
                             
                            
                            
                            
              
              
                            
                            
                            
                            
              
              
                            
        
                
        

    
    
    
    <!-- /section -->
    
        





                    

<!-- jQuery -->
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/jquery.js"></script>

<!-- Bootstrap Core JavaScript -->
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/bootstrap.min.js"></script>

<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/push/kitUtils.js"></script>
<!--script src="https://www.grab.com/id/wp-content/themes/grabsg/js/push/fastclick.min.js"></script-->
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/detectmobilebrowser.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/jquery.dataTables.min.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/dataTables.responsive.min.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/jquery.validate.min.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/slick.min.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/masonry.pkgd.min.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/imagesloaded.pkgd.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/jquery.flip.min.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/main.js?20170301"></script>

<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/jquery.simplePagination.js"></script>
<script src="https://www.grab.com/id/wp-content/themes/grabsg/js/swiper.js"></script>

<script>

$(".btn-download").click(function(event){
  event.preventDefault();
  
  if($.browser.mobile){
    
    var isiPad = /ipad/i.test(navigator.userAgent.toLowerCase());
    var isiPhone = /iphone/i.test(navigator.userAgent.toLowerCase());
    var isiPod = /ipod/i.test(navigator.userAgent.toLowerCase());
    var isAndroid = /android/i.test(navigator.userAgent.toLowerCase());
    
    var isiDevice = /ipad|iphone|ipod/i.test(navigator.userAgent.toLowerCase());
    var isBlackBerry = /blackberry/i.test(navigator.userAgent.toLowerCase());
    var isWebOS = /webos/i.test(navigator.userAgent.toLowerCase());
    var isWindowsPhone = /windows phone/i.test(navigator.userAgent.toLowerCase());
    
    if($(this).hasClass("driver")){
      if(isiDevice){window.location.href = "/id/download/driver/";}
      if (isAndroid){window.location.href = "https://play.google.com/store/apps/details?id=com.grabtaxi.driver2";}
      if (isBlackBerry){window.location.href = "/id/download/driver/";}
      if (isWebOS){window.location.href = "/id/download/driver/";}
      if (isWindowsPhone){window.location.href = "/id/download/driver/";}
    }else{
      if(isiDevice){window.location.href = "https://app.appsflyer.com/id647268330?pid=ID-Website-IOS-Install_Button&c=Website_Download";}
      if (isAndroid){window.location.href = "https://app.appsflyer.com/com.grabtaxi.passenger?pid=ID-Website-ADR-Install_Button&c=Website_Download";}
      if (isBlackBerry){window.location.href = "https://appworld.blackberry.com/webstore/content/44169887";}
      if (isWebOS){window.location.href = "/id/download/";}
      if (isWindowsPhone){window.location.href = "/id/download/";}
    }
  
  }
  else{
    if($(this).hasClass("driver")){window.location.href = "/id/download/driver/";}
    else{window.location.href = "/id/download/";}
  }
});

</script>
<script>

$(".innerLink").click(function(event) {
    event.preventDefault();
    $('html, body').animate({
      scrollTop: $(".goHere").offset().top
    }, 1500);
  });

     $(".section-carousel .carousel .item").css("height" , $(window).height() * 0.70);


   if($(".driverBanner .floatForm").length){
      var floatFormHeight = $(".driverBanner .floatForm").offset().top + $(".driverBanner .floatForm").innerHeight();
    var dBannerHeight = $(".driverBanner").height();

      if((floatFormHeight - dBannerHeight) > 8){

      var newHeight =  floatFormHeight - 8;
      var percentage = ($(window).height() - newHeight)/100;
      percentage = percentage.toFixed(2);


      $(".driverBanner").css("height" , newHeight);
     }

   }

   if($(window).width() <= 768 ){
    $(".driverBanner").css("height" , ($(window).height() * 0.85) +  $(".driverBanner .floatForm").height() );
      $(".section-carousel .carousel .item").css("height" , ($(window).height() * 0.85));
   }



  //FastClick.attach(document.body);

  
</script>

<script>
  // keep the dropdown open
  $('.dropdown-menu').on({
      "click":function(e){
        e.stopPropagation();
      }
  });

  // vertical tabs;
  $(document).ready(function() {
      $("div.grabnav-tab-menu>div.list-group>a").click(function(e) {
          e.preventDefault();
          var bg = $(this).attr('data-bg');
          $('#main-menu .dropdown-menu').css('background-image','linear-gradient(to right, rgba(246,248,250,1) 40%, rgba(246,248,250,0.5)), url('+bg+')');

          $(this).siblings('a.active').removeClass("active");
          $(this).addClass("active");
          var index = $(this).index();
          $("div.grabnav-tab>div.grabnav-tab-content").removeClass("active");
          $("div.grabnav-tab>div.grabnav-tab-content").eq(index).addClass("active");
      });
  });

  /****** New menu ********/
  $(document).mouseup(function(e){
      var container = $("#main-menu .multi-column,#main-menu .dropdown-toggle");
      if (!container.is(e.target) && container.has(e.target).length === 0){
          $('#main-menu .dropdown-toggle .bars').removeClass('hidden').toggleClass('show');
        $('#main-menu .dropdown-toggle .times').removeClass('show').toggleClass('hidden');

      }

      var partnerContainer = $("#secondary-menu .partner .multi-column, #secondary-menu .partner .dropdown-toggle");
      if (!partnerContainer.is(e.target) && partnerContainer.has(e.target).length === 0){
        $('#secondary-menu .partner .dropdown-toggle .fa').removeClass('fa-angle-up').addClass('fa-angle-down');
      }

      var langContainer = $("#secondary-menu .lang .multi-column, #secondary-menu .lang .dropdown-toggle");
      if (!langContainer.is(e.target) && langContainer.has(e.target).length === 0){
        $('#secondary-menu .lang .dropdown-toggle .fa').removeClass('fa-angle-up').addClass('fa-angle-down');
      }

      var searchContainer = $("#secondary-menu .search");
      if (!searchContainer.is(e.target) && searchContainer.has(e.target).length === 0){
          $('#secondary-menu .search input').val('').hide(200);
          $('#secondary-menu .search .fa-search').removeClass('search-submit');
      }

      // var mobileContainer = $("#mobile-menu .dropdown,#mobile-menu .dropdown-toggle");
      // if (!mobileContainer.is(e.target) && mobileContainer.has(e.target).length === 0){
      //     $('#mobile-menu .dropdown-toggle .bars').removeClass('hidden').toggleClass('show');
      //  $('#mobile-menu .dropdown-toggle .times').removeClass('show').toggleClass('hidden');

      // }

      var mobileSearchContainer = $("#mobile-menu .search");
      if (!mobileSearchContainer.is(e.target) && mobileSearchContainer.has(e.target).length === 0){
          $('#mobile-menu .search input').val('').hide(200);
    //       $('#top #mobile-menu .navbar-brand').animate({
      //     marginLeft: '68px'
      // }, 200);
      $('#mobile-menu .search .fa-search').removeClass('search-submit');
      }

  });
  $('#main-menu .dropdown-toggle').click(function() {
      $('#main-menu .dropdown-toggle .bars').removeClass('show').toggleClass('hidden');
      $('#main-menu .dropdown-toggle .times').removeClass('hidden').toggleClass('show');  
  });
  $('#mobile-menu .dropdown-toggle').click(function() {
    // $('#mobile-menu .dropdown-toggle .bars').removeClass('show').toggleClass('hidden');
   //    $('#mobile-menu .dropdown-toggle .times').removeClass('hidden').toggleClass('show');
  });

  // search box
  $('#secondary-menu .search .fa-search').click(function() {
    $(this).addClass('search-submit');
    $('#secondary-menu .search input').show(500);
  });

  // toggle down arrow;
  $('#secondary-menu .dropdown-toggle').click(function() {
    // var expand = $(this).attr('aria-expanded');

    // if(expand == 'true'){
    //  $(this).children('.fa').removeClass('fa-angle-up').toggleClass('fa-angle-down');
    // }else{
    //  $(this).children('.fa').removeClass('fa-angle-down').toggleClass('fa-angle-up');
    // }
  });
  // toggle down arrow;
  $('#mobile-menu .sub-menu-toggle').click(function() {
    // var open = $(this).hasClass('submenu-open');

    // if($(this).hasClass('submenu-open')){
    //  $(this).children('.fa').removeClass('fa-angle-down').toggleClass('fa-angle-right');
    // }else{
    //  $(this).children('.fa').removeClass('fa-angle-right').toggleClass('fa-angle-down');
    // }
  });
  
  $('#mobile-menu .search .fa-search').click(function() {
    $(this).addClass('search-submit');
    $('#mobile-menu .search input').show(500);
  });

  function searchBing(selector){
    var search = $(selector).val();
        search = search.trim();

      if(search !=''){
        search = search.replace(/<script[^>]*?>.*?<\/script>/gi, '').
        replace(/<[\/\!]*?[^<>]*?>/gi, '').
        replace(/<style[^>]*?>.*?<\/style>/gi, '').
        replace(/<![\s\S]*?--[ \t\n\r]*>/gi, '');

      window.location.href = "https://www.grab.com/id/search?key="+search;
      }
  }
  $(document).on("click",'#secondary-menu .search-submit.fa-search',function(e){
    searchBing('#secondary-menu .search input');  
  });
  $(document).on("click",'#mobile-menu .search-submit.fa-search',function(e){
    searchBing('#mobile-menu .search input'); 
  });

  $('#secondary-menu').on('keyup', '#search-key', function(e) {
    if (e.keyCode === 13) {
    e.preventDefault();
      searchBing('#secondary-menu .search input');
    }
  });

  $('#mobile-menu').on('keyup', '#mobile-search', function(e) {
    if (e.keyCode === 13) {
    e.preventDefault();
      searchBing('#mobile-menu .search input');
    }
  });

</script>
<script>//jQuery('<div id="survey-blue-bar"><a href="#" class="popmake-56241">How was your website experience?</a><a href="#" class="close-blue-bar visible-xs-inline">&times;</a></div>').appendTo('body');
//jQuery('.close-blue-bar').on('click', function() { jQuery('#survey-blue-bar').hide('fast'); });</script><script>jQuery(document).ready(function($) {
  salesforceForm = false;
  jQuery("form").each(function() {
    if (jQuery(this).attr('action').search(/salesforce/i) >= 0) {
      salesforceForm = true;
      id = jQuery(this).attr('id')
    }
  });

  if (salesforceForm) {
    jQuery('input[name="00N7F00000RuaYi"]').each(function() { $(this).attr('name', '00N7F00000RuaYi[]'); })
    jQuery('#sf-recaptcha').attr('data-sitekey', '6Le3PjIUAAAAAA6qH0HYORp6HKJhdxxH3f5iuA1e');

    jQuery('.msg-error').remove();
    jQuery('.elementor-field-type-submit').before('<div class="elementor-widget-form elementor-field-group"><p class="msg-error"></p></div>');
    jQuery('input[type="submit"]').before('<div class="col-sm-12 msg-error error"></div>');
    jQuery('.msg-error').addClass('error');

    jQuery('input').on('keyup', function () {
      if (jQuery("#"+id).valid()) {
            jQuery('form .submit-button').prop('disabled', false);
            jQuery('button[type="submit"]').prop('disabled', false);
        } else {
            jQuery('form .submit-button').prop('disabled', true);
          jQuery('button[type="submit"]').prop('disabled', true);
        }
    });

    jQuery('select').on('change', function () {
        if (jQuery("#"+id).valid()) {
            jQuery('form .submit-button').prop('disabled', false);
            jQuery('button[type="submit"]').prop('disabled', false);
        } else {
          jQuery('form .submit-button').prop('disabled', true);
          jQuery('button[type="submit"]').prop('disabled', true);
        }
    });

    jQuery("#"+id).off('submit');
    jQuery("#"+id).on('submit', function(e) {
      e.stopImmediatePropagation()
      e.preventDefault();
      if (jQuery("#"+id).valid()) {
        jQuery('form .submit-button').prop('disabled', true);
        jQuery('button[type="submit"]').prop('disabled', true);
        jQuery('.msg-error').html('');

        jQuery.ajax({
              url: '/wp-admin/admin-ajax.php?action=submitSalesforceForm',
              type: 'post',
              dataType: 'json',
              data: $(this).serialize(),
              success: function(data) {
                console.log(data);
                if (data.success) {
                  parameters        = '';
                  if ($('#partnershiptype').length) {
                    parameters = '?grabcom_form=2&grabcom_service=' + $('#partnershiptype').val();
                  }
                  else if ($('#Typeofpartnership').length) {
                    parameters = '?grabcom_form=2&grabcom_service=' + $('#Typeofpartnership').val();
                  }

                  location.href = jQuery("input[name='retURL']").val() + parameters;
                }
                else {
                  grecaptcha.reset();
                  jQuery('.msg-error').html(data.data.message);
                  console.log(data.data.sfMessage)
                }

                jQuery('form .submit-button').prop('disabled', false);
                jQuery('button[type="submit"]').prop('disabled', false);
                }
            });
        }
        else {
          jQuery('form .submit-button').prop('disabled', true);
          jQuery('button[type="submit"]').prop('disabled', true);
        }

        return false;
    });
  }
});</script><script type='text/javascript'>
/* <![CDATA[ */
var WPGlobus = {"version":"1.9.16","language":"id","enabledLanguages":["id","en"]};
/* ]]> */
</script>
<script type='text/javascript' src='https://www.grab.com/id/wp-content/plugins/wpglobus/includes/js/wpglobus.min.js?ver=1.9.16'></script>
<script type='text/javascript' src='https://www.grab.com/id/wp-includes/js/wp-embed.min.js?ver=4.9.8'></script>

</body>
</html>
