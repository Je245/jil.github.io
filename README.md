<!doctype html>
<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
<!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
<!--[if gt IE 8]><!-->
<html class="no-js">
<!--<![endif]-->
<head>
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<title>[TITLE]</title>
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0" />
[META]
<script type="text/javascript" src="assets/templates/common-html5/js/modernizr.min.js"></script>
<script type="text/javascript" src="assets/templates/common-html5/js/utilities.js"></script>
<link rel="stylesheet" href="assets/templates/common-html5/quicksearch/quicksearch.css" type="text/css" media="screen" />
<link rel="stylesheet" href="assets/templates/common-html5/css/layout.css" type="text/css" media="all" />
<link rel="stylesheet" href="assets/templates/common-html5/css/responsive.css" type="text/css" media="screen" />
<link rel="stylesheet" href="assets/templates/[template]/css/[stylesheet]" type="text/css" media="screen" />
<link href='https://fonts.googleapis.com/css?family=Open+Sans:400,600,700' rel='stylesheet' type='text/css' />
<link href='https://fonts.googleapis.com/css?family=Roboto+Slab:400,300,700' rel='stylesheet' type='text/css' />
<link rel="stylesheet" href="assets/templates/common-html5/css/fontello.css" />
<!--[if IE 7]>
<link rel="stylesheet" href="assets/templates/common-html5/css/fontello-ie7.css" />
<![endif]-->
<!--START: FRAME_RSSFEEDS -->
<link rel="alternate" type="application/rss+xml" title="Featured Items (RSS 2.0)" href="[store_url]/rss.asp?type=home" />
<link rel="alternate" type="application/rss+xml" title="Products On Sale (RSS 2.0)" href="[store_url]/rss.asp?type=onsale" />
<link rel="alternate" type="application/rss+xml" title="New Releases (RSS 2.0)" href="[store_url]/rss.asp?type=newreleases" />
<link rel="alternate" type="application/rss+xml" title="Best Sellers (RSS 2.0)" href="[store_url]/rss.asp?type=bestsellers" />
<link rel="alternate" type="application/rss+xml" title="Latest Blog Posts (RSS 2.0)" href="[store_url]/rss.asp?type=blog" />
<!--END: FRAME_RSSFEEDS -->
<script type="text/javascript">
    if (typeof jQuery == 'undefined') {
        document.write("<script type=\"text/javascript\" src=\"/assets/templates/common-html5/js/jquery.min.js\"></" + "script>");
    }
</script>
</head><body>
<div id="mainContainer">
  <div class="top-menu">
      <div class="wrapper">
      <a id="mobileMenu" class="show-mobile"><i class="icon-ellipsis-vert"></i></a>
      <a href="view_cart.asp" id="mobileCart" class="show-mobile"><i class="icon-basket"></i></a>
      <nav class="cbp-spmenu cbp-spmenu-vertical cbp-spmenu-left" id="showSlideMenu">
        <a id="closeSlideMenu" class="show-mobile"><i class="icon-cancel-circled"></i></a>
        <ul>
          <li class="m-search show-mobile">
              <div>
                <form method="get" name="mSearchForm" action="search.asp">
                  <input type="text" name="keyword" value="" placeholder="[frame_search]" />
                  <button name="search"><i class="icon-search"></i></button>
                  <div class="clear"></div>
                </form>
              </div>
          </li>
          <div class="mobile-catch"></div>
          <!--START: FRAME_MENU-->
            <!--START: menuitems_view--> 
            <!--START: TOP_LINK_FORMAT-->
            <li class="menu-links"><a href="infopage.asp?page=[link_id]" class="menu" target="[link_target]">[link_name]</a></li>
            <!--END: TOP_LINK_FORMAT--> 
            <!--END: menuitems_view-->
          <!--END: FRAME_MENU-->
        </ul>
        <div class="clear"></div>
        </nav>
          <div class="clear"></div>
      </div>
  </div>
  <header>
    <div class="wrapper">
      <div id="logo">
        <!--START: global_header-->
        <h1 class="store-name">[storename]</h1>
        <h3 class="store-slogan">[storeslogan]</h3>
        <!--END: global_header-->
      </div>
        <!--START: FRAME_SEARCH-->
          <div id="searchBox" class="hidden-mobile">
            <form method="get" name="searchForm" action="search.asp">
              <input type="text" id="searchlight" name="keyword" value="" placeholder="[frame_search]" />
              <input type="submit" name="search" value="" />
            </form>
            <div class="clear"></div>
          </div>
        <!--END: FRAME_SEARCH--> 
        <a id="cart" href="view_cart.asp" class="hidden-mobile"><img src="assets/templates/[template]/images/cart.png"><span id="noItems">[ITEMSINCART]</span> <span id="noItemsText">Item</span> in Cart</a>

        <div id="welcome-msg" class="welcome-msg">
          <!--START: login-->
            <a href="myaccount.asp">My Account</a> | Hi Guest, <a href="myaccount.asp">Login?</a>
          <!--END: login--> 
          <!--START: username-->
            <a href="myaccount.asp">My Account</a> | Hi [username], <a href="logout.asp">Logout</a>
          <!--END: username-->
        </div>
        <div class="clear"></div>
        <ul class="desktop-list"></ul>
        <div class="clear"></div>
    </div>
    <div class="clear"></div>
  </header>
  <nav id="catNavMenu">
    <div class="wrapper">
	<!--START: FRAME_CATEGORY-->
	<ul id="desktopMenu">
		<!--START: CATEGORIES-->
		<li>
			<!--START: CATEGORY_FORMAT-->
			<a href="view_category.asp?cat=CATID" class="cat">CATEGORY</a>
			<!--END: CATEGORY_FORMAT-->
			<ul class="subMenu">
			<!--START: SUB_CATEGORY_FORMAT-->
				<li><a href="view_category.asp?cat=CATID" class="subcat">CATEGORY</a></li>
			<!--END: SUB_CATEGORY_FORMAT-->
			</ul>
		</li>
		<!--END: CATEGORIES--> 
	</ul>
	<!--END: FRAME_CATEGORY-->
    <div class="clear"></div>
    </div>
  </nav>
  <div class="wrapper">
    <!--START: LEFT BAR-->
    <aside id="leftBar" class="leftBar">
      <div class="column" id="column1"> 
        <!--START: LEFT_BAR_BLOCKS-->
        <!--START: TOP_SELLERS_BLOCK-->
        <div id="modTopSellers" class="module"> <span class="menu-headers">[frame_top-sellers]</span>
          <div class="clear"></div>
          <!--START: topsellers--> 
          
          <!--START: topsellers_topitem-->
          <div class="topsellers_topitem">
            <div class="top-sellers-star">[ranking]</div>
            <div class="clear"></div>
            <div class="info">
              <div class="name"><a href="product.asp?itemid=[catalogid]" class="link">[name]</a></div>
              <div class="img"><a href="product.asp?itemid=[catalogid]" title="[name]"><img src="[thumbnail]" alt="[name]" /></a></div>
              <div class="clear"></div>
              <div class="price2"><!--START: ITEMPRICE--> 
                [ITEMPRICE] 
                <!--END: ITEMPRICE--> 
                <!--START: SALEPRICE--> 
                [ITEMSALEPRICE] 
                <!--END: SALEPRICE--></div>
              <div class="clear"></div>
              <div class="action"> <input type="button" value="[category_buyitlink]" onclick="window.location = 'add_cart.asp?quick=1&amp;item_id=[catalogid]'" class="btn" onmouseover="this.className='btn_over'" onmouseout="this.className='btn'" /></div>
            </div>
          </div>
          <div class="clear"></div>
          <!--END: topsellers_topitem--> 
          
          <!--START: topsellers_item-->
          <div class="div"></div>
          <div class="info">
            <div class="name"><a href="product.asp?itemid=[catalogid]" class="link">[name]</a></div>
            <div class="clear"></div>
            <!--START: product_review--> 
            <!--START: product_review_average-->
            <div class="stars"><img src="assets/templates/common-html5/images/star[review_average].png" alt="Average Rating" /></div>
            <!--END: product_review_average--> 
            <!--END: product_review-->
            <div class="price2"><!--START: ITEMPRICE--> 
              [ITEMPRICE] 
              <!--END: ITEMPRICE--> 
              <!--START: SALEPRICE--> 
              [ITEMSALEPRICE] 
              <!--END: SALEPRICE--></div>
          </div>
          <div class="clear"></div>
          <!--END: topsellers_item--> 
          
          <!--END: topsellers--> 
        </div>
        <!--END: TOP_SELLERS_BLOCK-->

        <!--START: NEW_RELEASES_BLOCK-->
        <div id="modNewReleases" class="module"> <span class="menu-headers">[frame_new-releases]</span>
          <div class="clear"></div>
          <!--START: newreleases--> 
          
          <!--START: newreleases_topitem-->
          <div class="info">
            <div class="name"><a href="product.asp?itemid=[catalogid]" class="link">[name]</a></div>
            <div class="clear"></div>
            <!--START: product_review--> 
            <!--START: product_review_average-->
            <div class="stars"><img src="assets/templates/common-html5/images/star[review_average].png" alt="Average Rating" /></div>
            <!--END: product_review_average--> 
            <!--END: product_review-->
            <div class="price2"><!--START: ITEMPRICE--> 
              [ITEMPRICE] 
              <!--END: ITEMPRICE--> 
              <!--START: SALEPRICE--> 
              [ITEMSALEPRICE] 
              <!--END: SALEPRICE--></div>
            <div class="clear"></div>
          </div>
          <div class="clear"></div>
          <!--END: newreleases_topitem--> 
          
          <!--START: newreleases_item-->
          <div class="div"></div>
          <div class="info">
            <div class="name"><a href="product.asp?itemid=[catalogid]" class="link">[name]</a></div>
            <div class="clear"></div>
            <!--START: product_review--> 
            <!--START: product_review_average-->
            <div class="stars"><img src="assets/templates/common-html5/images/star[review_average].png" alt="Average Rating" /></div>
            <!--END: product_review_average--> 
            <!--END: product_review-->
            <div class="price2"><!--START: ITEMPRICE--> 
              [ITEMPRICE] 
              <!--END: ITEMPRICE--> 
              <!--START: SALEPRICE--> 
              [ITEMSALEPRICE] 
              <!--END: SALEPRICE--></div>
            <div class="clear"></div>
          </div>
          <div class="clear"></div>
          <!--END: newreleases_item--> 
          
          <!--END: newreleases--> 
        </div>
        <!--END: NEW_RELEASES_BLOCK-->

        <!--START: FRAME_MANUFACTURER-->
        <div id="modManufacturers" class="module"> <span class="menu-headers">[frame_manufacturer]</span>
          <div class="clear"></div>
          <div id="modManufacturer">
              <ul>
                <!--START: manufacturer_format-->
                <li><a href="search_groups.asp?manf=[mfgid]" class="menu-bottom">[manufacturer]</a></li>
                <!--END: manufacturer_format-->
              </ul>
              <a href="manufacturer_index.asp" class="view-all-manf"><i class="icon-angle-right"></i> [frame_manufacturer-viewall]</a>
          </div>
          <div class="clear"></div>
        </div>
        <!--END: FRAME_MANUFACTURER-->

        <!--START: FRAME_BYPRICE-->
        <div id="modPrice" class="module"> <span class="menu-headers">[frame_byprice]</span>
          <ul>
            <!--START: byprice_format-->
            <li><a href="search_groups.asp?keyword=[id]&byprice=[id]" class="cat">[title]</a></li>
            <!--END: byprice_format-->
          </ul>
        </div>
        <!--END: FRAME_BYPRICE-->
        <!--START: LEFT_BANNER-->
        <div id="leftBanner">[LEFT_BANNER]</div>
        <!--END: LEFT_BANNER--> 
        <!--END: LEFT_BAR_BLOCKS--> 
      </div>
    </aside>
    <!--END: LEFT BAR-->
  <div id="mainContent">MIDDLE</div>
    <!--START: RIGHT BAR-->
    <aside id="rightBar" class="rightBar">
      <div class="column" id="column2"> 
        <!--START: RIGHT_BAR_BLOCKS--> 
        <!--START: RIGHT_BANNER-->
        <div id="rightBanner">[RIGHT_BANNER]</div>
        <!--END: RIGHT_BANNER--> 
        <!--END: RIGHT_BAR_BLOCKS--> 
      </div>
    </aside>
    <!--END: RIGHT BAR-->
  <div class="clear"></div>
  </div>
  <footer>
    <div class="wrapper"> 
      <div class="ftr-col col1">
      <!--START: FRAME_MAILLIST-->
      <div id="mailistBox">
        <form method="post" name="mailing" action="mailing_list.asp?action=add" onsubmit="return mailing_list();">
          <label>[frame_mailinglist]</label>
          <div class="mailist-box">
            <input type="text" name="email" value="" placeholder="Email Address" />
            <input type="submit" name="www" value="[mailinglist_button]" />
            <div class="clear"></div>
          </div>
          <input type="radio" name="subscribe" value="1" checked="checked" />
          <span class="menu-text">[mailinglist_subscribe]</span>
          <input type="radio" name="subscribe" value="0" />
          <span class="menu-text">[mailinglist_unsubscribe]</span>
          <div class="clear"></div>
        </form>
        <div class="clear"></div>
      </div>
      <!--END: FRAME_MAILLIST-->
      </div>
      <div class="ftr-col col2">
          <div class="social-icons"> 
            <!--START: social_link_facebook--><a href="[social_link_facebook_url]" class="facebook" target="_blank" title="Like Us on Facebook"><i class="icon-facebook"></i></a><!--END: social_link_facebook-->
            <!--START: social_link_twitter--><a href="[social_link_twitter_url]" class="twitter" target="_blank" title="Follow Us on Twitter"><i class="icon-twitter"></i></a><!--END: social_link_twitter-->
            <!--START: social_link_googleplus--><a href="[social_link_googleplus_url]" class="gplus" target="_blank" title="Follow Us on Google+"><i class="icon-gplus"></i></a><!--END: social_link_googleplus-->
            <!--START: social_link_youTube--><a href="[social_link_youTube_url]" class="youtube" target="_blank" title="Subscribe to Our Channel"><i class="icon-youtube-play"></i></a><!--END: social_link_youTube-->
            <!--START: social_link_pinterest--><a href="[social_link_pinterest_url]" class="pinterest" target="_blank" title="Follow Us on Pinterest"><i class="icon-pinterest-circled"></i></a><!--END: social_link_pinterest-->
            <!--START: social_link_instagram--><a href="[social_link_instagram_url]" class="instagram" target="_blank" title="Follow Us on Instagram"><i class="icon-instagramm"></i></a><!--END: social_link_instagram-->
            <!--START: social_link_tumblr--><a href="[social_link_tumblr_url]" class="tumblr" target="_blank" title="Follow Us on Tumblr"><i class="icon-tumblr"></i></a><!--END: social_link_tumblr-->
            <!--START: social_link_blog--><a href="[social_link_blog_url]" class="blog" target="_blank" title="Subscribe to our Blog"><i class="icon-rss"></i></a><!--END: social_link_blog-->
            <div class="clear"></div>
          </div>
      </div>
      <div class="clear"></div>
      <div id="globalFooter" class="footer">[GLOBAL_FOOTER]</div>
    </div>
    
  </footer>
  <div class="bottom-bar">
    <div class="wrapper">

      <div class="left">
        <div id="copyright" class="footer">[frame_copyright1]</div>
      </div>

      <div class="right">
        <div class="desktop-catch">
			<!--START: FRAME_LINKS-->
            <ul>
                <!--START: LINKS--> 
                <!--START: LINK_FORMAT-->
                <li><a href="infopage.asp?page=[link_id]&extra=1" target="[link_target]" class="menu-bottom">[link_name]</a></li>
                <!--END: LINK_FORMAT--> 
                <!--END: LINKS-->
            </ul>
            <!--END: FRAME_LINKS-->
        </div>
      </div>

    </div>
    <div class="clear"></div>
  </div>

</div>
<!--START: quicksearch--> 
<script type="text/javascript" src="assets/templates/common-html5/quicksearch/jquery.quicksearch.js"></script> 
<script type="text/javascript">
jQuery(function() {
	jQuery('#searchlight').searchlight('/search_quick.asp');
});
</script>
<!--END: quicksearch--> 
<script type="text/javascript" src="assets/templates/[template]/js/functions.js"></script>
<script type="text/javascript">
jQuery(document).ready(function () {
    jQuery('ul#desktopMenu').slicknav({
        prependTo: '.top-menu .wrapper',
        label: '',
        allowParentLinks: true,
        closedSymbol: '',
        openedSymbol: ''
    });

    if(jQuery(window).width() >= 1024 ) {
        jQuery('.menu-links').appendTo('.desktop-list');
    }
    
    if(jQuery(window).width() <= 1023 ) {
        jQuery('.menu-links').prependTo('.mobile-catch');
    }
});
</script>
<div class="stats"> 
  <!--START: 3dcart stats--> 
  <script type="text/javascript">
//<![CDATA[
var file='/stats/count.asp';

var stats_d=new Date();
var stats_s=stats_d.getSeconds();
var stats_m=stats_d.getMinutes();
var stats_x=stats_s*stats_m;
var prdID = '[catalogid]';
var catID = '[catid]';

stats_f='' + escape(document.referrer); stats_f=stats_f.replace('_','----');
if (navigator.appName=='Netscape'){stats_b='NS';}
if (navigator.appName=='Microsoft Internet Explorer'){stats_b='MSIE';}
if (navigator.appVersion.indexOf('MSIE 3')>0) {stats_b='MSIE';}
stats_u='' + escape(document.URL); stats_u=stats_u.replace('_','----'); stats_w=screen.width; stats_h=screen.height;
stats_v=navigator.appName;
stats_fs = window.screen.fontSmoothingEnabled;
if (stats_v != 'Netscape') {stats_c=screen.colorDepth;}
else {stats_c=screen.pixelDepth;}
stats_j=navigator.javaEnabled();
info='w=' + stats_w + '&h=' + stats_h + '&c=' + stats_c + '&r=' + stats_f + '&u='+ stats_u + '&fs=' + stats_fs + '&b=' + stats_b + '&x=' + stats_x + '&cat=' + catID + '&prd=' + prdID;
document.write('<img src="' + file + '?'+info+ '" width="1" height="1" border="0" alt="stats" />');
//]]>
</script>
  <noscript>
  <img src="/stats/count.asp" width="90" height="30" alt="" />
  </noscript>
  <!--END: 3dcart stats--> 
</div>
</body>
</html>
