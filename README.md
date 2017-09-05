# bootstrap-
bootstrap框架练习
css代码
body{margin:0;padding:0; font-size:12px; font-family:"SourceHanSansSC-Light","Microsoft Yahei",微软雅黑,"Helvetica Neue",Arial,sans-serif; width:100%;}
html,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,form,fieldset,input,textarea,blockquote,p,img{padding:0px; margin:0px;}
img{vertical-align:top; border:none;max-width:100%;}
button,select,textarea{outline:none}
figure,form,fieldset{border:0;margin:0;padding:0}
textarea{resize:none}
ul,li{list-style-type:none;}
textarea:focus,input:focus{outline:none;}
table{border-collapse:collapse; border-spacing:0; empty-cells:show; }
a,span,font,i,em{text-decoration:none;display:inline-block;}
a:hover{text-decoration:none;}

b,strong{font-weight:normal;}
cite,i{font-style:normal;}

.c:after {content:""; display:block; height:0; clear:both;}
.c{*zoom:1;}
.fl{float:left;}
.tc{text-align:center;}
.fr{float:right;}

@media {}
.nav>li{background:none;}
/*首页*/

.dashboard{width:100%;}
.chat li span img{border-radius:50%;}.chat-body{margin-right:60px;}
.chat .header{margin-left:60px;}.chat small{color:#77777F;}
.chatBody{overflow-y: scroll;}
.timeContent{border-bottom:#E7E7E7 1px solid;margin-bottom:16px;padding-bottom:16px;}

/*
 * metismenu - v1.1.3
 * Easy menu jQuery plugin for Twitter Bootstrap 3
 * https://github.com/onokumus/metisMenu
 *
 * Made by Osman Nuri Okumus
 * Under MIT License
 */
.arrow {
    float: right;
    line-height: 1.42857;
}

.glyphicon.arrow:before {
    content: "\e079";
}

.active > a > .glyphicon.arrow:before {
    content: "\e114";
}


/*
 * Require Font-Awesome
 * http://fortawesome.github.io/Font-Awesome/
*/


.fa.arrow:before {
    content: "\f104";
}

.active > a > .fa.arrow:before {
    content: "\f107";
}

.plus-times {
    float: right;
}

.fa.plus-times:before {
    content: "\f067";
}

.active > a > .fa.plus-times {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
}

.plus-minus {
    float: right;
}

.fa.plus-minus:before {
    content: "\f067";
}

.active > a > .fa.plus-minus:before {
    content: "\f068";
}
/*!
 * Start Bootstrap - SB Admin 2 v3.3.7+1 (http://startbootstrap.com/template-overviews/sb-admin-2)
 * Copyright 2013-2016 Start Bootstrap
 * Licensed under MIT (https://github.com/BlackrockDigital/startbootstrap/blob/gh-pages/LICENSE)
 */
body {
  background-color: #f8f8f8;
}
#wrapper {
  width: 100%;
}
#page-wrapper {
  padding: 0 15px;
  min-height: 568px;
  background-color: white;
}
@media (min-width: 768px) {
  #page-wrapper {
    position: inherit;
    margin: 0 0 0 250px;
    padding: 0 30px;
    border-left: 1px solid #e7e7e7;
  }
}
.navbar-top-links {
  margin-right: 0;
}
.navbar-top-links li {
  display: inline-block;
}
.navbar-top-links li:last-child {
  margin-right: 15px;
}
.navbar-top-links li a {
  padding: 15px;
  min-height: 50px;
}
.navbar-top-links .dropdown-menu li {
  display: block;
}
.navbar-top-links .dropdown-menu li:last-child {
  margin-right: 0;
}
.navbar-top-links .dropdown-menu li a {
  padding: 3px 20px;
  min-height: 0;
}
.navbar-top-links .dropdown-menu li a div {
  white-space: normal;
}
.navbar-top-links .dropdown-messages,
.navbar-top-links .dropdown-tasks,
.navbar-top-links .dropdown-alerts {
  width: 310px;
  min-width: 0;
}
.navbar-top-links .dropdown-messages {
  margin-left: 5px;
}
.navbar-top-links .dropdown-tasks {
  margin-left: -59px;
}
.navbar-top-links .dropdown-alerts {
  margin-left: -123px;
}
.navbar-top-links .dropdown-user {
  right: 0;
  left: auto;
}
.sidebar .sidebar-nav.navbar-collapse {
  padding-left: 0;
  padding-right: 0;
}
.sidebar .sidebar-search {
  padding: 15px;
}
.sidebar ul li {
 /* border-bottom: 1px solid #e7e7e7;*/
}
.sidebar ul li a.active {
  background-color: #eeeeee;
}
.sidebar .arrow {
  float: right;
}
.sidebar .fa.arrow:before {
  content: "\f104";
}
.sidebar .active > a > .fa.arrow:before {
  content: "\f107";
}
.sidebar .nav-second-level li,
.sidebar .nav-third-level li {
  border-bottom: none !important;
}
.sidebar .nav-second-level li a {
  padding-left: 37px;
}
.sidebar .nav-third-level li a {
  padding-left: 52px;
}
@media (min-width: 768px) {
  .sidebar {
    z-index: 1;
    position: absolute;
    width: 250px;
	margin-top: 51px;
  }
  .navbar-top-links .dropdown-messages,
  .navbar-top-links .dropdown-tasks,
  .navbar-top-links .dropdown-alerts {
    margin-left: auto;
  }
}
.btn-outline {
  color: inherit;
  background-color: transparent;
  transition: all .5s;
}
.btn-primary.btn-outline {
  color: #428bca;
}
.btn-success.btn-outline {
  color: #5cb85c;
}
.btn-info.btn-outline {
  color: #5bc0de;
}
.btn-warning.btn-outline {
  color: #f0ad4e;
}
.btn-danger.btn-outline {
  color: #d9534f;
}
.btn-primary.btn-outline:hover,
.btn-success.btn-outline:hover,
.btn-info.btn-outline:hover,
.btn-warning.btn-outline:hover,
.btn-danger.btn-outline:hover {
  color: white;
}
.chat {
  margin: 0;
  padding: 0;
  list-style: none;
}
.chat li {
  margin-bottom: 10px;
  padding-bottom: 5px;
  border-bottom: 1px dotted #999999;
}
.chat li.left .chat-body {
  margin-left: 60px;
}
.chat li.right .chat-body {
  margin-right: 60px;
}
.chat li .chat-body p {
  margin: 0;
}
.panel .slidedown .glyphicon,
.chat .glyphicon {
  margin-right: 5px;
}
.chat-panel .panel-body {
  height: 350px;
  overflow-y: scroll;
}
.login-panel {
  margin-top: 25%;
}
.flot-chart {
  display: block;
  height: 400px;
}
.flot-chart-content {
  width: 100%;
  height: 100%;
}
table.dataTable thead .sorting,
table.dataTable thead .sorting_asc,
table.dataTable thead .sorting_desc,
table.dataTable thead .sorting_asc_disabled,
table.dataTable thead .sorting_desc_disabled {
  background: transparent;
}
table.dataTable thead .sorting_asc:after {
  content: "\f0de";
  float: right;
  font-family: fontawesome;
}
table.dataTable thead .sorting_desc:after {
  content: "\f0dd";
  float: right;
  font-family: fontawesome;
}
table.dataTable thead .sorting:after {
  content: "\f0dc";
  float: right;
  font-family: fontawesome;
  color: rgba(50, 50, 50, 0.5);
}
.btn-circle {
  width: 30px;
  height: 30px;
  padding: 6px 0;
  border-radius: 15px;
  text-align: center;
  font-size: 12px;
  line-height: 1.428571429;
}
.btn-circle.btn-lg {
  width: 50px;
  height: 50px;
  padding: 10px 16px;
  border-radius: 25px;
  font-size: 18px;
  line-height: 1.33;
}
.btn-circle.btn-xl {
  width: 70px;
  height: 70px;
  padding: 10px 16px;
  border-radius: 35px;
  font-size: 24px;
  line-height: 1.33;
}
.show-grid [class^="col-"] {
  padding-top: 10px;
  padding-bottom: 10px;
  border: 1px solid #ddd;
  background-color: #eee !important;
}
.show-grid {
  margin: 15px 0;
}
.huge {
  font-size: 40px;
}
.panel-green {
  border-color: #5cb85c;
}
.panel-green > .panel-heading {
  border-color: #5cb85c;
  color: white;
  background-color: #5cb85c;
}
.panel-green > a {
  color: #5cb85c;
}
.panel-green > a:hover {
  color: #3d8b3d;
}
.panel-red {
  border-color: #d9534f;
}
.panel-red > .panel-heading {
  border-color: #d9534f;
  color: white;
  background-color: #d9534f;
}
.panel-red > a {
  color: #d9534f;
}
.panel-red > a:hover {
  color: #b52b27;
}
.panel-yellow {
  border-color: #f0ad4e;
}
.panel-yellow > .panel-heading {
  border-color: #f0ad4e;
  color: white;
  background-color: #f0ad4e;
}
.panel-yellow > a {
  color: #f0ad4e;
}
.panel-yellow > a:hover {
  color: #df8a13;
}
.timeline {
  position: relative;
  padding: 20px 0 20px;
  list-style: none;
}
.timeline:before {
  content: " ";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 50%;
  width: 3px;
  margin-left: -1.5px;
  background-color: #eeeeee;
}
.timeline > li {
  position: relative;
  margin-bottom: 20px;
}
.timeline > li:before,
.timeline > li:after {
  content: " ";
  display: table;
}
.timeline > li:after {
  clear: both;
}
.timeline > li:before,
.timeline > li:after {
  content: " ";
  display: table;
}
.timeline > li:after {
  clear: both;
}
.timeline > li > .timeline-panel {
  float: left;
  position: relative;
  width: 46%;
  padding: 20px;
  border: 1px solid #d4d4d4;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 6px rgba(0, 0, 0, 0.175);
  box-shadow: 0 1px 6px rgba(0, 0, 0, 0.175);
}
.timeline > li > .timeline-panel:before {
  content: " ";
  display: inline-block;
  position: absolute;
  top: 26px;
  right: -15px;
  border-top: 15px solid transparent;
  border-right: 0 solid #ccc;
  border-bottom: 15px solid transparent;
  border-left: 15px solid #ccc;
}
.timeline > li > .timeline-panel:after {
  content: " ";
  display: inline-block;
  position: absolute;
  top: 27px;
  right: -14px;
  border-top: 14px solid transparent;
  border-right: 0 solid #fff;
  border-bottom: 14px solid transparent;
  border-left: 14px solid #fff;
}
.timeline > li > .timeline-badge {
  z-index: 100;
  position: absolute;
  top: 16px;
  left: 50%;
  width: 50px;
  height: 50px;
  margin-left: -25px;
  border-radius: 50% 50% 50% 50%;
  text-align: center;
  font-size: 1.4em;
  line-height: 50px;
  color: #fff;
  background-color: #999999;
}
.timeline > li.timeline-inverted > .timeline-panel {
  float: right;
}
.timeline > li.timeline-inverted > .timeline-panel:before {
  right: auto;
  left: -15px;
  border-right-width: 15px;
  border-left-width: 0;
}
.timeline > li.timeline-inverted > .timeline-panel:after {
  right: auto;
  left: -14px;
  border-right-width: 14px;
  border-left-width: 0;
}
.timeline-badge.primary {
  background-color: #2e6da4 !important;
}
.timeline-badge.success {
  background-color: #3f903f !important;
}
.timeline-badge.warning {
  background-color: #f0ad4e !important;
}
.timeline-badge.danger {
  background-color: #d9534f !important;
}
.timeline-badge.info {
  background-color: #5bc0de !important;
}
.timeline-title {
  margin-top: 0;
  color: inherit;
}
.timeline-body > p,
.timeline-body > ul {
  margin-bottom: 0;
}
.timeline-body > p + p {
  margin-top: 5px;
}
@media (max-width: 767px) {
  ul.timeline:before {
    left: 40px;
  }
  ul.timeline > li > .timeline-panel {
    width: calc(10%);
    width: -moz-calc(10%);
    width: -webkit-calc(10%);
  }
  ul.timeline > li > .timeline-badge {
    top: 16px;
    left: 15px;
    margin-left: 0;
  }
  ul.timeline > li > .timeline-panel {
    float: right;
  }
  ul.timeline > li > .timeline-panel:before {
    right: auto;
    left: -15px;
    border-right-width: 15px;
    border-left-width: 0;
  }
  ul.timeline > li > .timeline-panel:after {
    right: auto;
    left: -14px;
    border-right-width: 14px;
    border-left-width: 0;
  }
}


js代码

/*
 * metismenu - v1.1.3
 * Easy menu jQuery plugin for Twitter Bootstrap 3
 * https://github.com/onokumus/metisMenu
 *
 * Made by Osman Nuri Okumus
 * Under MIT License
 */
;(function($, window, document, undefined) {

    var pluginName = "metisMenu",
        defaults = {
            toggle: true,
            doubleTapToGo: false
        };

    function Plugin(element, options) {
        this.element = $(element);
        this.settings = $.extend({}, defaults, options);
        this._defaults = defaults;
        this._name = pluginName;
        this.init();
    }

    Plugin.prototype = {
        init: function() {

            var $this = this.element,
                $toggle = this.settings.toggle,
                obj = this;

            if (this.isIE() <= 9) {
                $this.find("li.active").has("ul").children("ul").collapse("show");
                $this.find("li").not(".active").has("ul").children("ul").collapse("hide");
            } else {
                $this.find("li.active").has("ul").children("ul").addClass("collapse in");
                $this.find("li").not(".active").has("ul").children("ul").addClass("collapse");
            }

            //add the "doubleTapToGo" class to active items if needed
            if (obj.settings.doubleTapToGo) {
                $this.find("li.active").has("ul").children("a").addClass("doubleTapToGo");
            }

            $this.find("li").has("ul").children("a").on("click" + "." + pluginName, function(e) {
                e.preventDefault();

                //Do we need to enable the double tap
                if (obj.settings.doubleTapToGo) {

                    //if we hit a second time on the link and the href is valid, navigate to that url
                    if (obj.doubleTapToGo($(this)) && $(this).attr("href") !== "#" && $(this).attr("href") !== "") {
                        e.stopPropagation();
                        document.location = $(this).attr("href");
                        return;
                    }
                }

                $(this).parent("li").toggleClass("active").children("ul").collapse("toggle");

                if ($toggle) {
                    $(this).parent("li").siblings().removeClass("active").children("ul.in").collapse("hide");
                }

            });
        },

        isIE: function() { //https://gist.github.com/padolsey/527683
            var undef,
                v = 3,
                div = document.createElement("div"),
                all = div.getElementsByTagName("i");

            while (
                div.innerHTML = "<!--[if gt IE " + (++v) + "]><i></i><![endif]-->",
                all[0]
            ) {
                return v > 4 ? v : undef;
            }
        },

        //Enable the link on the second click.
        doubleTapToGo: function(elem) {
            var $this = this.element;

            //if the class "doubleTapToGo" exists, remove it and return
            if (elem.hasClass("doubleTapToGo")) {
                elem.removeClass("doubleTapToGo");
                return true;
            }

            //does not exists, add a new class and return false
            if (elem.parent().children("ul").length) {
                 //first remove all other class
                $this.find(".doubleTapToGo").removeClass("doubleTapToGo");
                //add the class on the current element
                elem.addClass("doubleTapToGo");
                return false;
            }
        },

        remove: function() {
            this.element.off("." + pluginName);
            this.element.removeData(pluginName);
        }

    };

    $.fn[pluginName] = function(options) {
        this.each(function () {
            var el = $(this);
            if (el.data(pluginName)) {
                el.data(pluginName).remove();
            }
            el.data(pluginName, new Plugin(this, options));
        });
        return this;
    };

})(jQuery, window, document);


/*!
 * Start Bootstrap - SB Admin 2 v3.3.7+1 (http://startbootstrap.com/template-overviews/sb-admin-2)
 * Copyright 2013-2016 Start Bootstrap
 * Licensed under MIT (https://github.com/BlackrockDigital/startbootstrap/blob/gh-pages/LICENSE)
 */
$(function() {
    $('#side-menu').metisMenu();
});

//Loads the correct sidebar on window load,
//collapses the sidebar on window resize.
// Sets the min-height of #page-wrapper to window size
$(function() {
    $(window).bind("load resize", function() {
        var topOffset = 50;
        var width = (this.window.innerWidth > 0) ? this.window.innerWidth : this.screen.width;
        if (width < 768) {
            $('div.navbar-collapse').addClass('collapse');
            topOffset = 100; // 2-row-menu
        } else {
            $('div.navbar-collapse').removeClass('collapse');
        }

        var height = ((this.window.innerHeight > 0) ? this.window.innerHeight : this.screen.height) - 1;
        height = height - topOffset;
        if (height < 1) height = 1;
        if (height > topOffset) {
            $("#page-wrapper").css("min-height", (height) + "px");
        }
    });

    var url = window.location;
    // var element = $('ul.nav a').filter(function() {
    //     return this.href == url;
    // }).addClass('active').parent().parent().addClass('in').parent();
    var element = $('ul.nav a').filter(function() {
        return this.href == url;
    }).addClass('active').parent();

    while (true) {
        if (element.is('li')) {
            element = element.parent().addClass('in').parent();
        } else {
            break;
        }
    }
});


html代码
<!doctype html>
	<head>
    	<title>bootstrapAdmin</title>
        
        <link href="css/index.css" rel="stylesheet"/>
        <link href="css/bootstrap.css" rel="stylesheet"/>
        <link href="css/metisMenu.css" rel="stylesheet">
        <link href="css/font-awesome.css" rel="stylesheet">
        <link href="css/sb-admin-2.css" rel="stylesheet">
        <script src="http://cdn.bootcss.com/jquery/1.11.1/jquery.min.js"></script>
        <script src="js/bootstrap.js"></script>
        <script src="js/metisMenu.js"></script>
        <script src="js/sb-admin-2.js"></script>
    </head>
    
    <body>
    	<!--nav-->
        <nav class="navbar navbar-default navbar-static-top"style="margin-bottom: 0">
            <div class="navbar-header">
            	<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a href="index.html" class="navbar-brand">SB Admin v2.0</a>
            </div>
            <ul class="nav navbar-top-links navbar-right">
                <li class="dropdown">
                    <a class="dropdown-toggle" data-toggle="dropdown" href="#">
                        <i class="fa fa-envelope fa-fw"></i> <i class="fa fa-caret-down"></i>
                    </a>
                    <ul class="dropdown-menu dropdown-messages">
                        <li>
                            <a href="#">
                                <div>
                                    <strong>John Smith</strong>
                                    <span class="pull-right text-muted">
                                        <em>Yesterday</em>
                                    </span>
                                </div>
                                <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque eleifend...</div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <strong>John Smith</strong>
                                    <span class="pull-right text-muted">
                                        <em>Yesterday</em>
                                    </span>
                                </div>
                                <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque eleifend...</div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <strong>John Smith</strong>
                                    <span class="pull-right text-muted">
                                        <em>Yesterday</em>
                                    </span>
                                </div>
                                <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque eleifend...</div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a class="text-center" href="#">
                                <strong>Read All Messages</strong>
                                <i class="fa fa-angle-right"></i>
                            </a>
                        </li>
                    </ul>
                </li>
                
                <li class="dropdown">
                    <a class="dropdown-toggle" data-toggle="dropdown" href="#">
                        <i class="fa fa-tasks fa-fw"></i> <i class="fa fa-caret-down"></i>
                    </a>
                    <ul class="dropdown-menu dropdown-tasks">
                        <li>
                            <a href="#">
                                <div>
                                    <p>
                                        <strong>Task 1</strong>
                                        <span class="pull-right text-muted">40% Complete</span>
                                    </p>
                                    <div class="progress progress-striped active">
                                        <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
                                            <span class="sr-only">40% Complete (success)</span>
                                        </div>
                                    </div>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <p>
                                        <strong>Task 2</strong>
                                        <span class="pull-right text-muted">20% Complete</span>
                                    </p>
                                    <div class="progress progress-striped active">
                                        <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100" style="width: 20%">
                                            <span class="sr-only">20% Complete</span>
                                        </div>
                                    </div>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <p>
                                        <strong>Task 3</strong>
                                        <span class="pull-right text-muted">60% Complete</span>
                                    </p>
                                    <div class="progress progress-striped active">
                                        <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
                                            <span class="sr-only">60% Complete (warning)</span>
                                        </div>
                                    </div>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <p>
                                        <strong>Task 4</strong>
                                        <span class="pull-right text-muted">80% Complete</span>
                                    </p>
                                    <div class="progress progress-striped active">
                                        <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%">
                                            <span class="sr-only">80% Complete (danger)</span>
                                        </div>
                                    </div>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a class="text-center" href="#">
                                <strong>See All Tasks</strong>
                                <i class="fa fa-angle-right"></i>
                            </a>
                        </li>
                    </ul>
                </li>
                
                <li class="dropdown">
                    <a class="dropdown-toggle" data-toggle="dropdown" href="#">
                        <i class="fa fa-bell fa-fw"></i> <i class="fa fa-caret-down"></i>
                    </a>
                    <ul class="dropdown-menu dropdown-alerts">
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-comment fa-fw"></i> New Comment
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-twitter fa-fw"></i> 3 New Followers
                                    <span class="pull-right text-muted small">12 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-envelope fa-fw"></i> Message Sent
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-tasks fa-fw"></i> New Task
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-upload fa-fw"></i> Server Rebooted
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a class="text-center" href="#">
                                <strong>See All Alerts</strong>
                                <i class="fa fa-angle-right"></i>
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="dropdown">
                    <a class="dropdown-toggle" data-toggle="dropdown" href="#">
                        <i class="fa fa-user fa-fw"></i> <i class="fa fa-caret-down"></i>
                    </a>
                    <ul class="dropdown-menu dropdown-user">
                        <li><a href="#"><i class="fa fa-user fa-fw"></i> User Profile</a>
                        </li>
                        <li><a href="#"><i class="fa fa-gear fa-fw"></i> Settings</a>
                        </li>
                        <li class="divider"></li>
                        <li><a href="login.html"><i class="fa fa-sign-out fa-fw"></i> Logout</a>
                        </li>
                    </ul>
                </li>
            </ul>
				
			<!--aside-->
            <aside class="navbar-default sidebar" role="na">
                <div class="sidebar-nav navbar-collapse">
                    <ul class="nav panel-group" id="side-menu">
                        <li class="sidebar-search">
                            <div class="input-group custom-search-form">
                                <input type="text" class="form-control" placeholder="Search...">
                                <span class="input-group-btn">
                                <button class="btn btn-default" type="button">
                                    <i class="fa fa-search"></i>
                                </button>
                            </span>
                            </div>
                        </li>
                        
                        <li>
                            <a href="index.html"><i class="fa fa-dashboard fa-fw"></i> Dashboard</a>
                        </li>
                        
                        <li class="panel">
                            <a data-toggle="collapse" data-parent="#side-menu" href="#aside01">
                            	<i class="fa fa-bar-chart-o fa-fw"></i> Charts<span class="fa arrow"></span>
                            </a>
                            <ul class="nav nav-second-level collapse panel-collapse" id="aside01">
                                <li>
                                    <a href="flot.html">Flot Charts</a>
                                </li>
                                <li>
                                    <a href="morris.html">Morris.js Charts</a>
                                </li>
                            </ul>
                        </li>
                        
                        <li>
                            <a href="tables.html"><i class="fa fa-table fa-fw"></i> Tables</a>
                        </li>
                        <li>
                            <a href="forms.html"><i class="fa fa-edit fa-fw"></i> Forms</a>
                        </li>
                        
                        <li class="panel">
                            <a data-toggle="collapse" data-parent="#side-menu" href="#aside02">
                            	<i class="fa fa-wrench fa-fw"></i> UI Elements<span class="fa arrow"></span>
                            </a>
                            <ul class="nav nav-second-level collapse panel-collapse" id="aside02">
                                <li>
                                    <a href="panels-wells.html">Panels and Wells</a>
                                </li>
                                <li>
                                    <a href="buttons.html">Buttons</a>
                                </li>
                                <li>
                                    <a href="notifications.html">Notifications</a>
                                </li>
                                <li>
                                    <a href="typography.html">Typography</a>
                                </li>
                                <li>
                                    <a href="icons.html"> Icons</a>
                                </li>
                                <li>
                                    <a href="grid.html">Grid</a>
                                </li>
                            </ul>
                        </li>
                        
                        <li class="panel">
                            <a data-toggle="collapse" data-parent="#side-menu" href="#aside03">
                            	<i class="fa fa-sitemap fa-fw"></i> Multi-Level Dropdown<span class="fa arrow"></span>
                            </a>
                            <ul class="nav nav-second-level collapse panel-collapse" id="aside03">
                                <li>
                                    <a href="#">Second Level Item</a>
                                </li>
                                <li>
                                    <a href="#">Second Level Item</a>
                                </li>
                                <li>
                                    <a data-toggle="collapse" href="#aside03-01">Third Level <span class="fa arrow"></span></a>
                                    <ul class="nav nav-third-level collapse panel-collapse" id="aside03-01">
                                        <li>
                                            <a href="#">Third Level Item</a>
                                        </li>
                                        <li>
                                            <a href="#">Third Level Item</a>
                                        </li>
                                        <li>
                                            <a href="#">Third Level Item</a>
                                        </li>
                                        <li>
                                            <a href="#">Third Level Item</a>
                                        </li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        
                        <li class="panel">
                            <a data-toggle="collapse" data-parent="#side-menu" href="#aside04">
                            	<i class="fa fa-files-o fa-fw"></i> Sample Pages<span class="fa arrow"></span>
                            </a>
                            <ul class="nav nav-second-level collapse panel-collapse" id="aside04">
                                <li>
                                    <a href="blank.html">Blank Page</a>
                                </li>
                                <li>
                                    <a href="login.html">Login Page</a>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </aside>
         </nav>
        
        
        <!--page-wrapper-->
        <div id="page-wrapper">
        	<div class="row">
            	<span class="col-lg-12"><h1 class="page-header">Dashboard</h1></span>
            </div>
            <div class="row">
            	<span class="col-lg-3">
                	<dl class="panel panel-primary"> 
                    	<dt class="panel-heading">
                        	<div  class="row">
                                <i class="fa fa-comments fa-5x col-xs-3"></i>
                                <div class="col-xs-9 text-right">
                                    <h2>26</h2><font>New Comments!</font>
                                </div>
                            </div>
                        </dt>
                        <a href="#" class="dashboard">
                            <dd class="panel-footer c">
                                <span>View Details</span><span class="pull-right"><i class="fa fa-arrow-circle-right"></i></span>
                            </dd>
                        </a>
                    </dl>
                </span>
                
                <span class="col-lg-3">
                	<dl class="panel panel-green"> 
                    	<dt class="panel-heading">
                        	<div  class="row">
                                <i class="fa fa-tasks fa-5x col-xs-3"></i>
                                <div class="col-xs-9 text-right">
                                    <h2>12</h2><font>New Tasks!</font>
                                </div>
                            </div>
                        </dt>
                        <a href="#" class="dashboard">
                            <dd class="panel-footer c">
                                <span>View Details</span><span class="pull-right"><i class="fa fa-arrow-circle-right"></i></span>
                            </dd>
                        </a>
                    </dl>
                </span>
                
                <span class="col-lg-3">
                	<dl class="panel panel-yellow"> 
                    	<dt class="panel-heading">
                        	<div  class="row">
                                <i class="fa fa-shopping-cart fa-5x col-xs-3"></i>
                                <div class="col-xs-9 text-right">
                                    <h2>124</h2><font>New Orders!</font>
                                </div>
                            </div>
                        </dt>
                        <a href="#"  class="dashboard">
                            <dd class="panel-footer c">
                                <span>View Details</span><span class="pull-right"><i class="fa fa-arrow-circle-right"></i></span>
                            </dd>
                        </a>
                    </dl>
                </span>
                
                <span class="col-lg-3">
                	<dl class="panel panel-red"> 
                    	<dt class="panel-heading">
                        	<div  class="row">
                                <i class="fa fa-support fa-5x col-xs-3"></i>
                                <div class="col-xs-9 text-right">
                                    <h2>13</h2><font>Support Tickets!</font>
                                </div>
                            </div>
                        </dt>
                        <a href="#" class="dashboard">
                            <dd class="panel-footer c">
                                <span>View Details</span><span class="pull-right"><i class="fa fa-arrow-circle-right"></i></span>
                            </dd>
                        </a>
                    </dl>
                </span>
            </div>
            
            <!--row-->
            <div class="row">
                <section class="col-lg-8">
                    <div class="panel panel-default">
                    	<div class="panel-heading">
                        	<i class="fa fa-bar-chart-o fa-fw"></i> Area Chart Example
                            <span class="pull-right">
                                <div class="btn-group">
                                	<button class="btn btn-default btn-xs dropdown-toggle" data-toggle="dropdown">
                                    	Actions<span class="caret"></span>
                                    </button>
                                    <ul class="dropdown-menu">
                                        <li><a href="#">Action</a></li>
                                        <li><a href="#">Another action</a></li>
                                        <li><a href="#">Something else here</a></li>
                                        <li class="divider"></li>
                                        <li><a href="#">Separated link</a></li>
                                    </ul>
                                </div>
                            </span>
                        </div>
                        <div class="panel-body">图表</div>
                    </div>
                    
                    <div class="panel panel-default">
                    	<div class="panel-heading">
                        	<i class="fa fa-bar-chart-o fa-fw"></i> Bar Chart Example
                            <span class="pull-right">
                                <div class="btn-group">
                                	<button class="btn btn-default btn-xs dropdown-toggle" data-toggle="dropdown">
                                    	Actions<span class="caret"></span>
                                    </button>
                                    <ul class="dropdown-menu">
                                        <li><a href="#">Action</a></li>
                                        <li><a href="#">Another action</a></li>
                                        <li><a href="#">Something else here</a></li>
                                        <li class="divider"></li>
                                        <li><a href="#">Separated link</a></li>
                                    </ul>
                                </div>
                            </span>
                        </div>
                        <div class="panel-body">
                        	<div class="row">
                            	<span class="col-lg-4">
                                	<table class="table table-bordered table-hover table-striped">
                                    	<thead>
                                        	<tr>
                                            	<th>#</th>
                                                <th>Date</th>
                                                <th>Time</th>
                                                <th>Amout</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                        	<tr>
                                            	<td>3326</td>
                                                <td>10/21/2013</td>
                                                <td>3:29 PM</td>
                                                <td>$321.33</td>
                                            </tr>
                                            <tr>
                                            	<td>3325</td>
                                                <td>10/21/2013</td>
                                                <td>3:20 PM</td>
                                                <td>$234.34</td>
                                            </tr>
                                            <tr>
                                            	<td>3324</td>
                                                <td>10/21/2013</td>
                                                <td>3:03 PM</td>
                                                <td>$724.17</td>
                                            </tr>
                                            <tr>
                                            	<td>3323</td>
                                                <td>10/21/2013</td>
                                                <td>3:00 PM</td>
                                                <td>$23.71</td>
                                            </tr>
                                            <tr>
                                            	<td>3322</td>
                                                <td>10/21/2013</td>
                                                <td>2:49 PM</td>
                                                <td>$8345.23</td>
                                            </tr>
                                            <tr>
                                            	<td>3321</td>
                                                <td>10/21/2013</td>
                                                <td>2:23 PM</td>
                                                <td>$245.12</td>
                                            </tr>
                                            <tr>
                                            	<td>3320</td>
                                                <td>10/21/2013</td>
                                                <td>2:15 PM</td>
                                                <td>$5663.54</td>
                                            </tr>
                                            <tr>
                                            	<td>3319</td>
                                                <td>10/21/2013</td>
                                                <td>2:13 PM</td>
                                                <td>$5663.54</td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </span>
                                <span class="col-lg-4">图表</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="panel panel-default c">
                    	<div class="panel-heading">
                        	<i class="fa fa-clock-o fa-fw"></i> Responsive Timeline
                        </div>
                        <div class="panel-body">
                        	<ul class="timeline c">
                            	<li>
                                	<div class="timeline-badge gray"><i class="fa fa-check"></i></div>
                                    <div class="timeline-panel">
                                    	<div>
                                        	<h4>Lorem ipsum dolor</h4><p><small><i class="fa fa-clock-o"></i> 11 hours ago via Twitter</small></p>
                                        </div>
                                        <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero laboriosam dolor perspiciatis omnis exercitationem. Beatae, officia pariatur? Est cum veniam excepturi. Maiores praesentium, porro voluptas suscipit facere rem dicta, debitis.</div>
                                    </div>
                                    
                                </li>
                                <li class="timeline-inverted c">
                                	<div class="timeline-badge warning pull-left"><i class="fa fa-credit-card"></i></div>
                                    <div class="timeline-panel pull-right">
                                    	<span><h4>Lorem ipsum dolor</h4></span>
                                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem dolorem quibusdam, tenetur commodi provident cumque magni voluptatem libero, quis rerum. Fugiat esse debitis optio, tempore. Animi officiis alias, officia repellendus.
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laudantium maiores odit qui est tempora eos, nostrum provident explicabo dignissimos debitis vel! Adipisci eius voluptates, ad aut recusandae minus eaque facere.</span>
                                    </div>
                                </li>
                                <li>
                                	<div class="timeline-badge danger"><i class="fa fa-bomb"></i></div>
                                    <div class="timeline-panel">
                                    	<span><h4>Lorem ipsum dolor</h4></span>
                                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus numquam facilis enim eaque, tenetur nam id qui vel velit similique nihil iure molestias aliquam, voluptatem totam quaerat, magni commodi quisquam.</span>
                                    </div>
                                </li>
                                <li class="timeline-inverted">
                                    <div class="timeline-panel">
                                    	<span><h4>Lorem ipsum dolor</h4></span>
                                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates est quaerat asperiores sapiente, eligendi, nihil. Itaque quos, alias sapiente rerum quas odit! Aperiam officiis quidem delectus libero, omnis ut debitis!</span>
                                    </div>
                                </li>
                                <li>
                                	<div class="timeline-badge info"><i class="fa fa-save"></i></div>
                                    <div class="timeline-panel">
                                    	<span><h4>Lorem ipsum dolor</h4></span>
                                        <div class="timeContent">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nobis minus modi quam ipsum alias at est molestiae excepturi delectus nesciunt, quibusdam debitis amet, beatae consequuntur impedit nulla qui! Laborum, atque.</div>					
                                        <div class=" btn-group">
                                            <button class="btn btn-primary btn-sm dropdown-toggle" data-toggle="dropdown">
                                                <i class="fa fa-gear"></i><span class="caret"></span>
                                            </button>
                                            <ul class="dropdown-menu">
                                                <li><a href="#">Action</a></li><li><a href="#">Another action</a></li>
                                                <li><a href="#">Something else here</a></li><li class="divider"></li><li><a href="#">Separated link</a></li>
                                            </ul>
                                        </div>
                                    </div>
                                </li>
                                <li class="timeline-inverted">
                                    <div class="timeline-panel">
                                    	<span><h4>Lorem ipsum dolor</h4></span>
                                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi fuga odio quibusdam. Iure expedita, incidunt unde quis nam! Quod, quisquam. Officia quam qui adipisci quas consequuntur nostrum sequi. Consequuntur, commodi.</span>
                                    </div>
                                </li>
                                <li class="timeline-inverted">
                                	<div class="timeline-badge success"><i class="fa fa-graduation-cap"></i></div>
                                    <div class="timeline-panel">
                                    	<span><h4>Lorem ipsum dolor</h4></span>
                                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt obcaecati, quaerat tempore officia voluptas debitis consectetur culpa amet, accusamus dolorum fugiat, animi dicta aperiam, enim incidunt quisquam maxime neque eaque.</span>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </section>
                
                
                <section class="col-lg-4">
                	<div class="panel panel-default">
                    	<div class="panel-heading">
                        	<i class="fa fa-bell fa-fw"></i> Notifications Panel
                        </div>
                        <div class="panel-body">
                        	<div class="list-group">
                            	<a href="#" class="list-group-item">
                                	<i class="fa fa-comment fa-fw"></i> New Comment
                                	<span class="small pull-right text-muted"><em>4 minutes ago</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-twitter fa-fw"></i> 3 New Followers
                                	<span class="small pull-right text-muted"><em>12 minutes ago</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-envelope fa-fw"></i> Message Sent
                                	<span class="small pull-right text-muted"><em>27 minutes ago</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-tasks fa-fw"></i> New Task
                                	<span class="small pull-right text-muted"><em>43 minutes ago</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-upload fa-fw"></i>  Server Rebooted
                                	<span class="small pull-right text-muted"><em>11:32 AM</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-bolt fa-fw"></i> Server Crashed!
                                	<span class="small pull-right text-muted"><em>11:13 AM</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-warning fa-fw"></i> Server Not Responding
                                	<span class="small pull-right text-muted"><em>10:57 AM</em></span>
                                </a>
                                <a href="#" class="list-group-item">
                                	<i class="fa fa-shopping-cart fa-fw"></i> New Order Placed
                                	<span class="small pull-right text-muted"><em>9:49 AM</em></span>
                                </a>
								<a href="#" class="list-group-item">
                                	<i class="fa fa-money fa-fw"></i> Payment Received
                                	<span class="small pull-right text-muted"><em>Yesterday</em></span>
                                </a>
                            </div>
                            <a href="#" class="btn btn-default btn-block">View All Alerts</a>
                        </div>
                    </div>
                    
                    <div class="panel panel-default">
                    	<div class="panel-heading">
                        	<i class="fa fa-bar-chart-o fa-fw"></i> Donut Chart Example
                        </div>
                        
                        <div class="panel-body">
                        	<a href="#" class="btn btn-default btn-block">View Details</a>
                        </div>
                    </div>
                    
                    <div class="panel panel-default">
                    	<div class="panel-heading">
                        	<i class="fa fa-comments fa-fw"></i> Chat
                            <span class="btn-group pull-right">
                            	<button class="btn btn-default btn-xs btn-sm dropdown-toggle" data-toggle="dropdown">
                                	<i class="fa fa-chevron-down"></i>
                                </button>
                                <ul class="dropdown-menu">
                                	<li><a href="#"><i class="fa fa-refresh fa-fw"></i> Refresh</a></li>
                                    <li><a href="#"><i class="fa fa-check-circle fa-fw"></i>  Available</a></li> 
                                    <li><a href="#"><i class="fa fa-times fa-fw"></i> Busy</a></li>  
                                    <li><a href="#"><i class="fa fa-clock-o fa-fw"></i>  Away</a></li>  
                                    <li class="divider"></li> 
                                	<li><a href="#"><i class="fa fa-sign-out fa-fw"></i> Sign Out</a></li>  
                                                   
                                </ul>
                            </span>
                        </div>
                        
                        <div class="panel-body chatBody">
                        	<ul class="chat c">
                            	<li>
                                	<span class="pull-left"><img src="http://placehold.it/50/55C1E7/fff"></span>
                                   	<div class="header">
                                    	<div>
                                        	<strong>Jack Sparrow</strong>
                                            <small class="fr"><i class="fa fa-clock-o fa-fw"></i> 12 mins ago</small>
                                        </div>
                                    	<p>
                                        	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur bibendum ornare dolor, quis ullamcorper ligula sodales.
                                        </p>
                                    </div>
                                </li>
                                
                                <li class="c">
                                    <span class="pull-right"><img src="http://placehold.it/50/FA6F57/fff"></span>
                                   	<div class="chat-body">
                                    	<div>
                                        	<strong class="fr">Jack Sparrow</strong>
                                            <small><i class="fa fa-clock-o fa-fw"></i> 12 mins ago</small>
                                        </div>
                                    	<p>
                                        	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur bibendum ornare dolor, quis ullamcorper ligula sodales.
                                        </p>
                                    </div>
                                </li>
                                
                                <li>
                                	<span class="pull-left"><img src="http://placehold.it/50/55C1E7/fff"></span>
                                   	<div class="header">
                                    	<div>
                                        	<strong>Jack Sparrow</strong>
                                            <small class="fr"><i class="fa fa-clock-o fa-fw"></i> 12 mins ago</small>
                                        </div>
                                    	<p>
                                        	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur bibendum ornare dolor, quis ullamcorper ligula sodales.
                                        </p>
                                    </div>
                                </li>
                                
                                <li class="c">
                                    <span class="pull-right"><img src="http://placehold.it/50/FA6F57/fff"></span>
                                   	<div class="chat-body">
                                    	<div>
                                        	<strong class="fr">Jack Sparrow</strong>
                                            <small><i class="fa fa-clock-o fa-fw"></i> 12 mins ago</small>
                                        </div>
                                    	<p>
                                        	Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur bibendum ornare dolor, quis ullamcorper ligula sodales.
                                        </p>
                                    </div>
                                </li>
                            </ul>
                        </div>
                        <div class="panel-footer">
                            <div class="input-group">
                                <input class="form-control input-sm" placeholder="Type your message here...">
                                <span class="input-group-btn">
                                    <button class="btn btn-warning btn-sm">Send</button>
                                </span>
                            </div>
                        </div>
                    </div>
                </section>
                
            </div>
        </div>
    </body>
</html>
