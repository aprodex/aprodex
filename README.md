<!DOCTYPE html>
<html lang="en">
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <!-- Meta, title, CSS, favicons, etc. -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>:: EDUSYS - I.E.P. ALFONSO UGARTE ::</title>
	<link rel="shortcut icon" href="../../img/login/logo_edusys.ico" />
	<link href="../../img/login/logo_edusys.png" rel="apple-touch-icon-precomposed">

    <!-- Bootstrap -->
    <link href="vendors/bootstrap/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link href="vendors/font-awesome/css/font-awesome.min.css" rel="stylesheet">
    <link rel="stylesheet" href="vendors/font-awesome-animation/font-awesome-animation.css">

    <link rel="stylesheet" href="fonts/edusys.css">

    <!-- PNotify -->
    <link href="vendors/pnotify/dist/pnotify.css" rel="stylesheet">
    <link href="vendors/pnotify/dist/pnotify.buttons.css" rel="stylesheet">
    <link href="vendors/pnotify/dist/pnotify.nonblock.css" rel="stylesheet">

    <link href="vendors/pace/pace-theme-flash.css" rel="stylesheet">
    <link href="vendors/lightbox/ekko-lightbox.css" rel="stylesheet">
    <!-- NProgress -->
    <!--<link href="vendors/nprogress/nprogress.css" rel="stylesheet">-->
    <!-- iCheck -->
    <link href="vendors/iCheck/skins/flat/green.css" rel="stylesheet"><!---->
    <!-- bootstrap-progressbar -->
    <!--<link href="vendors/bootstrap-progressbar/css/bootstrap-progressbar-3.3.4.min.css" rel="stylesheet">-->
    <!-- JQVMap -->
    <!--<link href="vendors/jqvmap/dist/jqvmap.min.css" rel="stylesheet"/>-->
    <link rel="stylesheet" type="text/css" href="js/bootstrap-select-1.11.2/dist/css/bootstrap-select.css">
    <link rel="stylesheet" type="text/css" href="js/typeahead/typeahead.bundle.css"> 

    <!-- SUMMERNOTE -->
    <link rel="stylesheet" type="text/css" href="js/summernote/summernote-bs4.css">

    <!-- Ladda style -->
    <link href="js/ladda/ladda-themeless.min.css" rel="stylesheet">


    <!-- Custom Theme Style -->
    <link href="build/css/custom.css" rel="stylesheet">
    
   
<script type="text/javascript">

/***********************************************
* Local Time script- Ãƒâ€šÃ‚Â© Dynamic Drive (http://www.dynamicdrive.com)
* This notice MUST stay intact for legal use
* Visit http://www.dynamicdrive.com/ for this script and 100s more.
***********************************************/

var weekdaystxt=["Dom", "Lun", "Mar", "Mie", "Jue", "Vie", "Sab"]

function showLocalTime(container, servermode, offsetMinutes, displayversion){
if (!document.getElementById || !document.getElementById(container)) return
this.container=document.getElementById(container)
this.displayversion=displayversion
var servertimestring=(servermode=="server-php")? 'August 23, 2022 17:17:18' : (servermode=="server-ssi")? '<!--#config timefmt="%B %d, %Y %H:%M:%S"--><!--#echo var="DATE_LOCAL" -->' : '<%= Now() %>'
this.localtime=this.serverdate=new Date(servertimestring)
this.localtime.setTime(this.serverdate.getTime()+offsetMinutes*60*1000) //add user offset to server time
this.updateTime()
this.updateContainer()
}

showLocalTime.prototype.updateTime=function(){
var thisobj=this
this.localtime.setSeconds(this.localtime.getSeconds()+1)
setTimeout(function(){thisobj.updateTime()}, 1000) //update time every second
}

showLocalTime.prototype.updateContainer=function(){
var thisobj=this
if (this.displayversion=="long")
this.container.innerHTML=this.localtime.toLocaleString()
else{
var hour=this.localtime.getHours()
var minutes=this.localtime.getMinutes()
var seconds=this.localtime.getSeconds()
var ampm=(hour>=12)? "PM" : "AM"
var dayofweek=weekdaystxt[this.localtime.getDay()]
this.container.innerHTML=formatField(hour, 1)+":"+formatField(minutes)+":"+formatField(seconds)+" "+ampm;//+" ("+dayofweek+")"
}
setTimeout(function(){thisobj.updateContainer()}, 1000) //update container every second
}

function formatField(num, isHour){
if (typeof isHour!="undefined"){ //if this is the hour field
var hour=(num>12)? num-12 : num
return (hour==0)? 12 : hour
}
return (num<=9)? "0"+num : num//if this is minute or sec field
}

</script>
<style>

.note_common, .bignote, .editinfo{
	padding: 20px 10px 10px 10px;
	color: #000;
	float: left;
	margin: 20px;
	margin-top: 0;
	position: relative;
	cursor: pointer;
	border: 3px solid white;
	/* page effect start */
	-webkit-border-bottom-left-radius: 20px 500px;
	-webkit-border-bottom-right-radius: 500px 30px;
	-webkit-border-top-right-radius: 5px 100px;
	-moz-border-radius-bottomleft: 20px 500px;
	-moz-border-radius-bottomright: 500px 30px;
	-moz-border-radius-topright: 5px 100px;
	border-radius-bottomleft: 20px 500px;
	border-radius-bottomright: 500px 30px;
	border-radius-topright: 5px 100px;
	-webkit-box-shadow: 0 2px 10px 1px rgba(0,0,0,.2);
	-moz-box-shadow: 0 2px 10px 1px rgba(0,0,0,.2);
	box-shadow: 0 2px 10px 1px rgba(0,0,0,.2);
	/* page effect end */

	-moz-box-shadow: -7px 10px rgba(0,0,0,0.3);
	-webkit-box-shadow: -7px 10px rgba(0,0,0,0.3);
	box-shadow: -7px 10px rgba(0,0,0,0.3);
	
	
}


/* for rotation start */
.rotateR{
   -moz-transform:    rotate(3deg);
   -o-transform:      rotate(3deg);
   -webkit-transform: rotate(3deg);
   transform:         rotate(3deg);

/*
 * The following two rules are for IE only and
 * should be wrapped in conditional comments.
 * The -ms-filter rule should be on one line 
 * and always *before* the filter rule if
 * used in the same rule.
 */

   /* IE8+ - must be on one line, unfortunately */ 
   -ms-filter: "progid:DXImageTransform.Microsoft.Matrix(M11=0.9986295347545738, M12=-0.05233595624294437, M21=0.05233595624294437, M22=0.9986295347545738, SizingMethod='auto expand')";
   
   /* IE6 and 7 */ 
   filter: progid:DXImageTransform.Microsoft.Matrix(
            M11=0.9986295347545738,
            M12=-0.05233595624294437,
            M21=0.05233595624294437,
            M22=0.9986295347545738,
            SizingMethod='auto expand');


   /*
    * To make the transform-origin be the middle of
    * the object.    Note: These numbers
    * are approximations.  For more accurate results,
    * use Internet Explorer with this tool.
    */
   margin-left: -4px; 
   margin-top: -8px;
}

.rotateL{
   -moz-transform:    rotate(-3deg);
   -o-transform:      rotate(-3deg);
   -webkit-transform: rotate(-3deg);
   transform:         rotate(-3deg);

   -ms-filter: "progid:DXImageTransform.Microsoft.Matrix(M11=0.9986295347545738, M12=0.05233595624294388, M21=-0.05233595624294388, M22=0.9986295347545738, SizingMethod='auto expand')";
   
   filter: progid:DXImageTransform.Microsoft.Matrix(
            M11=0.9986295347545738,
            M12=0.05233595624294388,
            M21=-0.05233595624294388,
            M22=0.9986295347545738,
            SizingMethod='auto expand');

   margin-left: -4px; 
   margin-top: -8px;
}
/* for rotation end */

.note_common h2{
    text-align:center;
    margin-top:0;
    padding-top:0;
    font-family: cursive;
}

.note_common p{
    font-size:0.9em;
    overflow:auto;
    overflow-x:hidden;
    line-height:18px;
    text-align:left;
    font-family: 'Architects Daughter', cursive;
}

.inset{
   -moz-box-shadow:inset 0 0 10px #cccccc;
   -webkit-box-shadow:inset 0 0 10px #cccccc;
   box-shadow:inset 0 0 10px #cccccc;
   background:#f8f7f7;
   color:#333;
   padding:5px;
   font-size:0.9em;
   border:1px solid #e7e7e7;
   font-family: 'Architects Daughter', cursive;
}

input:focus,textarea:focus,select:focus{border:1px solid #fafafa;-webkit-box-shadow:0 0 6px #000;-moz-box-shadow:0 0 5px #000;box-shadow:0 0 5px #000;}

.tip{
   background:url(../img/tip.png) no-repeat;
   font-size:13px;
   padding-left:25px;
   padding-top:3px;
   vertical-align:middle;
}

.icons-footer .ficon{
   margin-left:10px;
   position:absolute;
   bottom:-15px;
}

/* for sticky note background oolors */

.stickynote0 {
   background-color: #99FF41;
   background-image: -webkit-gradient(linear, left top, left bottom, from(#99FF41), to(#53B00A)); 
   background-image: -webkit-linear-gradient(top, #99FF41, #53B00A); 
   background-image:    -moz-linear-gradient(top, #99FF41, #53B00A); 
   background-image:     -ms-linear-gradient(top, #99FF41, #53B00A); 
   background-image:      -o-linear-gradient(top, #99FF41, #53B00A); 
   background-image:         linear-gradient(top, #99FF41, #53B00A);
   filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#99FF41', EndColorStr='#53B00A');
}

.stickynote1 {
   background-color: #3889C5;
   color:#FFFFFF;
   background-image: -webkit-gradient(linear, left top, left bottom, from(#3889C5), to(#024B7E)); 
   background-image: -webkit-linear-gradient(top, #3889C5, #024B7E); 
   background-image:    -moz-linear-gradient(top, #3889C5, #024B7E); 
   background-image:     -ms-linear-gradient(top, #3889C5, #024B7E); 
   background-image:      -o-linear-gradient(top, #3889C5, #024B7E); 
   background-image:         linear-gradient(top, #3889C5, #024B7E);
   filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#3889C5', EndColorStr='#024B7E');
}

.stickynote2 {
    background-color: #FF4FBF;
	color:#FFFFFF;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#FF4FBF), to(#C61684)); 
    background-image: -webkit-linear-gradient(top, #FF4FBF, #C61684); 
    background-image:    -moz-linear-gradient(top, #FF4FBF, #C61684); 
    background-image:     -ms-linear-gradient(top, #FF4FBF, #C61684); 
    background-image:      -o-linear-gradient(top, #FF4FBF, #C61684); 
    background-image:         linear-gradient(top, #FF4FBF, #C61684);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#FF4FBF', EndColorStr='#C61684');
}

.stickynote3{
    background-color: #FF3F1E;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#FF3F1E), to(#F02504)); 
    background-image: -webkit-linear-gradient(top, #FF3F1E, #F02504); 
    background-image:    -moz-linear-gradient(top, #FF3F1E, #F02504); 
    background-image:     -ms-linear-gradient(top, #FF3F1E, #F02504); 
    background-image:      -o-linear-gradient(top, #FF3F1E, #F02504); 
    background-image:         linear-gradient(top, #FF3F1E, #F02504);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#FF3F1E', EndColorStr='#F02504');
}

.stickynote4{
    background-color: #DCC37D;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#DCC37D), to(#988744)); 
    background-image: -webkit-linear-gradient(top, #DCC37D, #988744); 
    background-image:    -moz-linear-gradient(top, #DCC37D, #988744); 
    background-image:     -ms-linear-gradient(top, #DCC37D, #988744); 
    background-image:      -o-linear-gradient(top, #DCC37D, #988744); 
    background-image:         linear-gradient(top, #DCC37D, #988744);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#DCC37D', EndColorStr='#988744');
}

.stickynote5{
    background-color: #5F36BC;
	color:#FFFFFF;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#5F36BC), to(#250082)); 
    background-image: -webkit-linear-gradient(top, #5F36BC, #250082); 
    background-image:    -moz-linear-gradient(top, #5F36BC, #250082); 
    background-image:     -ms-linear-gradient(top, #5F36BC, #250082); 
    background-image:      -o-linear-gradient(top, #5F36BC, #250082); 
    background-image:         linear-gradient(top, #5F36BC, #250082);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#5F36BC', EndColorStr='#250082');
}

.stickynote6{
    background-color: #A5C2FF;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#A5C2FF), to(#6986F4)); 
    background-image: -webkit-linear-gradient(top, #A5C2FF, #6986F4); 
    background-image:    -moz-linear-gradient(top, #A5C2FF, #6986F4); 
    background-image:     -ms-linear-gradient(top, #A5C2FF, #6986F4); 
    background-image:      -o-linear-gradient(top, #A5C2FF, #6986F4); 
    background-image:         linear-gradient(top, #A5C2FF, #6986F4);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#A5C2FF', EndColorStr='#6986F4');
}

.stickynote7{
    background-color: #FEBFBF;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#FEBFBF), to(#FE8080)); 
    background-image: -webkit-linear-gradient(top, #FEBFBF, #FE8080); 
    background-image:    -moz-linear-gradient(top, #FEBFBF, #FE8080); 
    background-image:     -ms-linear-gradient(top, #FEBFBF, #FE8080); 
    background-image:      -o-linear-gradient(top, #FEBFBF, #FE8080); 
    background-image:         linear-gradient(top, #FEBFBF, #FE8080);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#FEBFBF', EndColorStr='#FE8080');
}

.stickynote8{
    background-color: #FEBF80;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#FEBF80), to(#FF8000)); 
    background-image: -webkit-linear-gradient(top, #FEBF80, #FF8000); 
    background-image:    -moz-linear-gradient(top, #FEBF80, #FF8000); 
    background-image:     -ms-linear-gradient(top, #FEBF80, #FF8000); 
    background-image:      -o-linear-gradient(top, #FEBF80, #FF8000); 
    background-image:         linear-gradient(top, #FEBF80, #FF8000);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#FEBF80', EndColorStr='#FF8000');
}

.stickynote9{
    background-color: #FEF280;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#FEF280), to(#FFE500)); 
    background-image: -webkit-linear-gradient(top, #FEF280, #FFE500); 
    background-image:    -moz-linear-gradient(top, #FEF280, #FFE500); 
    background-image:     -ms-linear-gradient(top, #FEF280, #FFE500); 
    background-image:      -o-linear-gradient(top, #FEF280, #FFE500); 
    background-image:         linear-gradient(top, #FEF280, #FFE500);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorStr='#FEF280', EndColorStr='#FFE500');
}
.fa.fa-thumb-tack {  
    transform: rotate(390deg);
	font-size:45px;
	color:#1e65b0;
	z-index:999999;
}
.oval {
	width: 25px;
	height: 8px;
	background: black;
	-moz-border-radius: 100px / 50px;
	-webkit-border-radius: 100px / 50px;
	border-radius: 100px / 50px;
	position: absolute; 
	left:9%;
	top: 115%; 
	-moz-opacity:0.5;
	-khtml-opacity: 0.5;    
	opacity:0.5; 
	filter:alpha(opacity=50);
}
</style>
  </head>

  <body class="nav-md page-register  pace-done">
 
    <div class="pace  pace-inactive">
    <div data-progress="99" data-progress-text="100%" style="transform: translate3d(100%, 0px, 0px);" class="pace-progress">
    	<div class="pace-progress-inner"></div>
    </div>
    <div class="pace-activity"></div>
    </div>

    <div class="container body">
      <div class="main_container">
        <div class="col-md-3 left_col">
          <div class="left_col scroll-view">
            <div class="navbar nav_title" style="border: 0;">
              <!--<a href="index.php" class="site_title"><span><img src="images/institucion.png" height="40" width="40" class="img-responsive"></span> <span>I.S.T.P. CAPECO</span></a>-->
              <div class="navbar nav_title" style="border: 0;">
              <a  class="site_title css_ruta"  url="main_edusys.php">
              <!--<i class="fa icon-institucion" style="font-size:35px"></i> <i class="fa fa-paw"></i>-->
              <center><br>
            <img src="../../img/logo.png" height="100" width="100" class="img-responsive">
    
              
              <span>I.E.P. ALFONSO UGARTE</span>
              </center>
              
              </a>
            </div>
            </div>

            <div class="clearfix"></div>

            <!-- menu profile quick info -->
            <div class="profile">
              <div class="profile_pic">
                <img src="../../img/alumnos/nofoto.jpg" alt="..." id="img_familia" name="img_familia" class="img-circle profile_img">
              </div>
              <div class="profile_info">
                <span>Bienvenida Familia: </span>
                <h2>ALCANTARA ESPINOZA</h2>
              </div>
            </div>
            <!-- /menu profile quick info -->

            <br />

            <!-- sidebar menu -->
            <div id="sidebar-menu" class="main_menu_side hidden-print main_menu">
              <div class="menu_section">
                <h3></h3>
                <ul class="nav side-menu">


<li class="active css_li_menu" url="main_edusys.php"><a class="css_ruta" ><i class="fs1 i-edusys-home4"></i> Inicio </a></li>
<li class=" css_li_menu" url="info_personal_edusys.php"><a class="css_ruta" ><i class="fs1 i-edusys-familia-1"></i>  Familia  </a>
</li>
<li class=" css_li_menu" url="pagos_edusys.php"><a class="css_ruta" ><i class="fs1 i-edusys-pagos"></i>  Pensiones  </a>
</li>
<li class=" css_li_menu" url="notas_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-uniE603"></i> Mis Notas  </a></li>
<!--<li class=" css_li_menu" url="companieros_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-estudiantes-1"></i> Compa&ntilde;eros </a></li>-->
<li class=" css_li_menu" url="profesores_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-profesor-1"></i> Profesores </a></li>
<li class=" css_li_menu " url="aula_virtual_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-uniE609" ></i> Agenda </a></li>
<li class=" css_li_menu " url="psicologia_edusys.php"><a class="css_ruta"> <i class="fs1 i-edusys-psicologia_alumno" ></i> Psicologia&nbsp;&nbsp; </a></li>
<!--<li class=" css_li_menu" url="circulares_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-bullhorn"></i> Circulares </a></li>-->
<li class=" css_li_menu" url="consejo_educativo_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-colegio"></i> Consejo Educativo </a> </li>

<li class=" css_li_menu" url="tareas_linea_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-colegio"></i>  Mis Tareas </a> </li>


<!--<li class=" css_li_menu" url="companieros_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-companieros-mix-capeco"></i> Compa&ntilde;eros </a> </li>
<li class=" css_li_menu" url="profesores_edusys.php"><a class="css_ruta"><i class="fs1 i-edusys-instructor-capeco"></i> Profesores </a></li>-->
                </ul>
              </div>
              <div class="menu_section" style="display:none">
                <h3>Live On</h3>
                <ul class="nav side-menu">
                  <li><a><i class="fa fa-bug"></i> Additional Pages <span class="fa fa-chevron-down"></span></a>
                    <ul class="nav child_menu">
                      <li><a href="e_commerce.html">E-commerce</a></li>
                      <li><a href="projects.html">Projects</a></li>
                      <li><a href="project_detail.html">Project Detail</a></li>
                      <li><a href="contacts.html">Contacts</a></li>
                      <li><a href="profile.html">Profile</a></li>
                    </ul>
                  </li>
                  <li><a><i class="fa fa-windows"></i> Extras <span class="fa fa-chevron-down"></span></a>
                    <ul class="nav child_menu">
                      <li><a href="page_403.html">403 Error</a></li>
                      <li><a href="page_404.html">404 Error</a></li>
                      <li><a href="page_500.html">500 Error</a></li>
                      <li><a href="plain_page.html">Plain Page</a></li>
                      <li><a href="login.html">Login Page</a></li>
                      <li><a href="pricing_tables.html">Pricing Tables</a></li>
                    </ul>
                  </li>
                  <li><a><i class="fa fa-sitemap"></i> Multilevel Menu <span class="fa fa-chevron-down"></span></a>
                    <ul class="nav child_menu">
                        <li><a href="#level1_1">Level One</a>
                        <li><a>Level One<span class="fa fa-chevron-down"></span></a>
                          <ul class="nav child_menu">
                            <li class="sub_menu"><a href="level2.html">Level Two</a>
                            </li>
                            <li><a href="#level2_1">Level Two</a>
                            </li>
                            <li><a href="#level2_2">Level Two</a>
                            </li>
                          </ul>
                        </li>
                        <li><a href="#level1_2">Level One</a>
                        </li>
                    </ul>
                  </li>
                  <li><a href="javascript:void(0)"><i class="fa fa-laptop"></i> Landing Page <span class="label label-success pull-right">Coming Soon</span></a></li>
                </ul>
              </div>

            </div>
            <!-- /sidebar menu -->

            <!-- /menu footer buttons -->
            <div class="sidebar-footer hidden-small">
              <a   data-placement="top" title="Cambiar contrase&ntilde;a" style="cursor:pointer" data-toggle="modal" data-target=".bs-change-password-modal-lg">
                <span class="glyphicon i-edusys-change-password" style="color:#00BD7F; font-size:20px" aria-hidden="true"></span><!--glyphicon-cog-->
              </a>
              <a data-toggle="tooltip" data-placement="top" title="Pantalla Completa" class="waves-effect waves-button waves-classic toggle-fullscreen">
                <span class="glyphicon glyphicon-fullscreen" aria-hidden="true"></span>
              </a>
              <a data-toggle="tooltip" data-placement="top" title="Ayuda"  style="cursor:pointer">
                <span class="glyphicon glyphicon-question-sign" style="color:#2492E1" aria-hidden="true"></span>
              </a>
              <a data-toggle="tooltip" data-placement="top" title="Salir" href="../../modulos/inludes/salir_session.php"  style="cursor:pointer">
                <span class="glyphicon glyphicon-off" style="color:#F00" aria-hidden="true"></span>
              </a>
            </div>
            <!-- /menu footer buttons -->
          </div>
        </div>

        <!-- top navigation -->
        <div class="top_nav">
          <div class="nav_menu">

            <nav>
              <div class="nav toggle">
                <a id="menu_toggle"><i class="fa fa-bars"></i></a>
              </div>
              <!-- top left nav -->
                <ul id="ul-navbar-nav" class="nav navbar-nav navbar-left">
                    <li class="toggle-sidebar">
                        <a >
                            <i class="fa fa-calendar"></i> Martes 23 de Agosto de 2022                        </a>
                    </li>
                    <li>
                        <a   ><i class="fa fa-clock-o"></i> <span id="timecontainer"></span></a> 
                  </li>
                </ul>
                <!-- / top left nav -->
              <ul class="nav navbar-nav navbar-right">
				
                <li class="">
                  <a href="javascript:;" class="user-profile dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
                    <img src="../../img/alumnos/nofoto.jpg" alt="" id="img_perfil" name="img_perfil"><span id="span_nomperfil">Alvaro Jhosue</span>
                    <span class=" fa fa-angle-down"></span>
                  </a>
                  <ul class="dropdown-menu dropdown-usermenu pull-right">
                    <li><a  class="css_ruta" url="info_personal_edusys.php"> Informaci&oacute;n Personal</a></li>
                    <li>
                      <a href="javascript:;" data-toggle="modal" data-target=".bs-change-password-modal-lg">
                      <i class="fa i-edusys-change-password pull-right"></i> Cambiar Contrase&ntilde;a</a>
                      </a>
                    </li>
                    <li><a href="javascript:;"><i class="fa fa-question-circle pull-right"></i> Ayuda</a></li>
                    <li><a href="../../modulos/inludes/salir_session.php"><i class="fa fa-sign-out pull-right"></i> Salir</a></li>
                  </ul>
                </li>
                                <li role="presentation" class="dropdown" style="display:nonez">
                  <a href="javascript:;" class="dropdown-toggle info-number" data-toggle="dropdown" aria-expanded="false">
                    <i class="fa i-edusys-uniE616" style="font-size:35px"></i>
                    <span class="badge bg-green">2</span>
                  </a>
                  <ul id="menu1" class="dropdown-menu list-unstyled msg_list" role="menu">
                                      <li class="css_li_hermanos" codalu="20142351" secmat="180" urlfot="../../img/alumnos/nofoto.jpg" nomalu="Alvaro Jhosue">
                      <a>
                        <span class="image"><img src="../../img/alumnos/nofoto.jpg" alt="ALCANTARA ALCANTARA, Alvaro Jhosue" /></span>
                        <span>
                          <span>Alvaro Jhosue</span>
                          <span class="time">4to SECUNDARIA - A</span>
                        </span>
                        <span class="message">
                          Tutor: GUERRERO RIOS, GUILLERMO<br>Auxiliar: ACEVEDO AGUILAR Juan                        </span>
                      </a>
                    </li>
                                        <li class="css_li_hermanos" codalu="20163878" secmat="166" urlfot="../../img/alumnos/nofoto.jpg" nomalu="Said Alexander">
                      <a>
                        <span class="image"><img src="../../img/alumnos/nofoto.jpg" alt="ALCANTARA ALCANTARA, Said Alexander" /></span>
                        <span>
                          <span>Said Alexander</span>
                          <span class="time">4to PRIMARIA - C</span>
                        </span>
                        <span class="message">
                          Tutor: LEVANO URBINA, JHOANA LIZ<br>Auxiliar: ACEVEDO AGUILAR Juan                        </span>
                      </a>
                    </li>
                      
                    <!--
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <div class="text-center">
                        <a>
                          <strong>See All Alerts</strong>
                          <i class="fa fa-angle-right"></i>
                        </a>
                      </div>
                    </li>-->
                  </ul>
                </li>
                                <li role="presentation" class="dropdown" style="display:none">
                  <a href="javascript:;" class="dropdown-toggle info-number" data-toggle="dropdown" aria-expanded="false">
                    <i class="fa fa-envelope-o"></i>
                    <span class="badge bg-green">6</span>
                  </a>
                  <ul id="menu1" class="dropdown-menu list-unstyled msg_list" role="menu">
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <a>
                        <span class="image"><img src="images/img.jpg" alt="Profile Image" /></span>
                        <span>
                          <span>John Smith</span>
                          <span class="time">3 mins ago</span>
                        </span>
                        <span class="message">
                          Film festivals used to be do-or-die moments for movie makers. They were where...
                        </span>
                      </a>
                    </li>
                    <li>
                      <div class="text-center">
                        <a>
                          <strong>See All Alerts</strong>
                          <i class="fa fa-angle-right"></i>
                        </a>
                      </div>
                    </li>
                  </ul>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <!-- /top navigation -->

        <!-- page content -->
        <div class="right_col" role="main" id="div_main">


          <br />
          <div class="row">



            <div class="col-md-8 col-sm-8 col-xs-12">



              <div class="row">



              </div>
              <div class="row">


                <!-- Start to do list -->

                <!-- End to do list -->

                <!-- start of weather widget -->

                <!-- end of weather widget -->
              </div>
            </div>




          </div>
        </div>
        <!-- /page content -->

        <!-- footer content -->
        <footer>
          <div class="pull-right">
            :: EDUSYS - I.E.P. ALFONSO UGARTE :: por <a href="http://www.digitechdata.pe/" target="_blank">Edusys-DigitechData</a>
          </div>
          <div class="clearfix"></div>
        </footer>
        <!-- /footer content -->
      </div>
    </div>

    <div id="div_modal_change_password" class="modal fade bs-change-password-modal-lg" tabindex="-1" role="dialog" aria-hidden="true">
<div class="modal-dialog modal-lg">
  <div class="modal-content">

    <div class="modal-header">
      <button type="button" class="close" data-dismiss="modal"><i class="fa fa-close"></i></button>
      <h4 class="modal-title" id="myModalLabel"><i class="fa fa-key"></i> ACTUALIZAR CONTRASE&Ntilde;A</h4>
    </div>
    <div class="modal-body">

    	<div id="div_change_password">

        <div class="panel panel-default">
                    <div class="panel-body">
                        <div class="text-center">
                          <h3><i class="fa i-edusys-change-password fa-4x"></i></h3>
                          <h2 class="text-center">Desea actualizar su contrase&ntilde;a?</h2>
                          <p>Complete los siguientes datos.</p>
                            <div class="panel-body">

                              <form id="form_change_password" name="form_change_password" class="form-group">
                                <fieldset>
                                  <div class="form-group">
                                    <div class="input-group">
                                      <span class="input-group-addon"><i class="fa fa-key color-blue"></i></span>

                                      <input id="password_original" name="password_original" placeholder="ingrese contrase&ntilde;a actual" class="form-control css_password"  required="" type="password" value="" autocomplete="false">
                                    </div>
                                  </div>
                                  <div class="form-group">
                                    <div class="input-group">
                                      <span class="input-group-addon"><i class="fa fa-lock color-blue"></i></span>
                                      <input id="password_chage" name="password_chage" placeholder="ingrese nueva contrase&ntilde;a actual" class="form-control css_password"  required="" type="password" value="" autocomplete="false">
                                    </div>
                                  </div>
                                   <div class="form-group">
                                    <div class="input-group">
                                      <span class="input-group-addon"><i class="fa fa-lock color-blue"></i></span>
                                      <input id="password_chage_conf" name="password_chage_conf" placeholder="confirme nueva contrase&ntilde;a actual" class="form-control css_password"  required="" type="password" value="" autocomplete="false">
                                    </div>
                                  </div>
                                  <div class="form-group">
                                  <i class="fa fa-exclamation-triangle"></i> La contrase&ntilde;a es alfanumerico.
                                  </div>
                                  <div class="form-group">
                                  <button type="submit" id="cmb_change_password" name="cmb_change_password" class="btn btn-lg btn-default btn-block">Actualizar mi contrase&ntilde;a <i style="display:none" class="fa fa-spinner faa-spin animated"></i> </button> <!--btn btn-round btn-default-->
                                  </div>
                                </fieldset>
                              </form>

                            </div>
                        </div>
                    </div>
                </div>

        </div>

    </div>

  </div>
</div>
</div>
  
<!-- Modal Encuesta PPFF-->
 
 
<!-- Modal Encuesta -->
<!-- Modal Cronograma de matricula -->
<div id="myModal-DatosPersonales" class="modal fade" data-keyboard="false" data-backdrop="static">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header"> 
                <h4 class="modal-title"> ADMINISTRACIÓN DE DATOS PERSONALES</h4>
            </div>
            <div class="modal-body" >
            <div style="font-size:14px; text-align:justify; margin-left:5%; margin-right:5%; margin-top:5%">
            De acuerdo a lo establecido en la Ley N° 29733, Ley de Protección de Datos Personales, y el Decreto Supremo N° 003-2013-JUS, por el que se aprueba su Reglamento, el C.E.P. Alfonso Ugarte, informa a los Usuarios de los Sitios Web, canales de información, plataformas, redes sociales, formularios digitales, aplicaciones, así como cualquier medio electrónico o digital equivalente que la Información del Usuario será incorporada a los bancos de datos de titularidad de la Institución.
		   <br><br>
A través de la presente Política de Privacidad el Usuario da su consentimiento expreso para la inclusión de su información en los mencionados bancos de datos.<br><br>
Para lo cual el C.E.P. Alfonso Ugarte adopta las medidas técnicas y organizativas necesarias para garantizar la protección de la Información del Usuario y evitar su alteración, pérdida, tratamiento y/o acceso no autorizado, habida cuenta del estado de la técnica, la naturaleza de los datos almacenados y los riesgos a que están expuestos.<br><br>
En ese sentido, el C.E.P. Alfonso Ugarte usará los estándares en materia de protección de la confidencialidad de la Información del Usuario.<br><br>
</div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default css_aceptar_privacidad">ACEPTAR</button> 
            </div>
        </div>
    </div>
</div>
<!-- Modal pagos pendienstes matricula -->
<div id="myModal-PagosPendientesMatricula" class="modal fade" data-keyboard="false" data-backdrop="static">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header"> 
                <h4 class="modal-title">COMUNICADO</h4>
            </div>
            <div class="modal-body" >
            <div style="font-size:24px; text-align:justify; margin-left:5%; margin-right:5%; margin-top:5%">
            Tiene pagos pendientes por el concepto de matrícula,  sírvase regularizar los mismo acercándose a las oficinas de la CAJA CUSCO.<br><br>Gracias.</div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default css_cerrar_sistema">ACEPTAR</button> 
            </div>
        </div>
    </div>
</div>
<!-- Modal view notas -->
<div id="myModal-ViewNotas" class="modal fade" data-keyboard="false" data-backdrop="static">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <h4 class="modal-title">DETALLE DE NOTAS</h4>
            </div>
            <div class="modal-body" >
                <div id="div-view-notdet" style="font-size:24px; text-align:justify; margin-left:5%; margin-right:5%; margin-top:5%">

                </div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default  close"  data-dismiss="modal">ACEPTAR</button>
            </div>
        </div>
    </div>
</div>

<!-- Modal view examen -->
<div id="myModal-ViewExamen" class="modal fade" data-keyboard="false" data-backdrop="static">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <h4 class="modal-title">EXAMEN</h4>
            </div>
            <div class="modal-body" >
                <div id="div-view-examen" style="font-size:16px; text-align:justify; margin-left:1%; margin-right:1%; margin-top:2%">

                </div>
            </div>
            <div class="modal-footer">

            </div>
        </div>
    </div>
</div>


<!-- ###########################################################################################################[TROZO VISTA ADJUNTO TAREA] -->


<div id="myModal-ViewTarea" class="modal fade" data-keyboard="false" data-backdrop="static">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
            	<button type="button" class="close" data-dismiss="modal"><i class="fa fa-close"></i></button>
                <h4 class="modal-title">TAREA</h4>
            </div>
            <div class="modal-body" >
            	<div class="mail-body">
<form>
  <div class="form-group row">
    <label for="restar_para" class="col-sm-2 col-form-label">Para:</label>
    <div class="col-sm-10">
      <input type="text" readonly class="form-control-plaintext" id="restar_para" name="restar_para" value="">
    </div>
  </div>
  <div class="form-group row">
    <label for="restar_curso" class="col-sm-2 col-form-label">Curso:</label>
    <div class="col-sm-10">
      <input type="text" readonly class="form-control-plaintext" id="restar_curso" name="restar_curso" value="">
    </div>
  </div>
  <div class="form-group row">
    <label for="restar_asunto" class="col-sm-2 col-form-label">Asunto:</label>
    <div class="col-sm-10">
      <input type="text" readonly class="form-control-plaintext" id="restar_asunto" name="restar_asunto" value="">
    </div>
  </div>
   <div class="form-group row show-progress" style="display:none;">
		 <div class="progress skill-bar ">
                <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">
                    <span class="skill"><i class="val">100%</i></span>
                </div>
        </div>
  </div>





  <div class="form-group row show-attach">
    <label for="restar_adjunto" class="col-sm-2 col-form-label">Adjunto:</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="restar_adjunto" name="restar_adjunto" placeholder="Documento">
	  <div  style="font-size: 16px;font-weight:bold;margin-top:7px;margin-bottom:7px;">pdf|doc|xls|ppt|docx|xlsx|pptx|txt|jpg</div>
      <span id="upload_button"><span style="font-size: 18px;cursor:pointer;" class="fa fa-paperclip"></span>Adjuntar respuestar </span> Max. 2MB
    </div>
  </div>


</form>


                </div>

                    <div class="mail-text h-200">

                        <div class="css-summernote-tarea">


                        </div>
<div class="clearfix"></div>
                        </div>
                <div id="div-view-tarea" style="font-size:16px; text-align:justify; margin-left:1%; margin-right:1%; margin-top:2%">

                </div>
            </div>
            <div class="modal-footer">
                 <button type="button" class="btn btn-default css-btn-send-respuesta-tarea"   >ENVIAR RESPUESTA</button>
            </div>
        </div>
    </div>
</div>

<!-- ########################################################################################################### -->

<input name="totpreenc" id="totpreenc" type="hidden" value="" />


    <!-- jQuery -->
    <script src="vendors/jquery/dist/jquery.min.js"></script>
    <!-- Bootstrap -->
    <script src="vendors/bootstrap/dist/js/bootstrap.min.js"></script>
    <!-- FastClick -->
    <script src="vendors/fastclick/lib/fastclick.js"></script>
    <!-- NProgress -->
    <!--<script src="vendors/nprogress/nprogress.js"></script>-->
    <!-- Chart.js -->
   <!-- <script src="vendors/Chart.js/dist/Chart.min.js"></script>-->
    <!-- gauge.js -->
    <script src="vendors/gauge.js/dist/gauge.min.js"></script>
    <!-- bootstrap-progressbar -->
    <!--<script src="vendors/bootstrap-progressbar/bootstrap-progressbar.min.js"></script>-->
    <!-- iCheck -->
  <!--  <script src="vendors/iCheck/icheck.min.js"></script>-->
    <!-- PNotify -->

	<script src="vendors/bootstrap-progressbar/bootstrap-progressbar.min.js"></script>
    <script src="vendors/pnotify/dist/pnotify.js"></script>
    <script src="vendors/pnotify/dist/pnotify.buttons.js"></script>
    <script src="vendors/pnotify/dist/pnotify.nonblock.js"></script>
    <script src="vendors/angular/angular.min.js"></script>
    <script src="vendors/pace/pace.js"></script>

    <script src="vendors/jquery.validate/jquery.validate.js"></script>

    <script src="vendors/bootstrap-responsive-tabs/responsive-tabs.js"></script>
    <!-- bootstrap-daterangepicker -->
   <!-- <script src="production/js/moment/moment.min.js"></script>
    <script src="production/js/datepicker/daterangepicker.js"></script>-->
    <!-- bootstrap-datepicker -->
    <link rel="stylesheet" type="text/css" href="vendors/bootstrap-datepicker/css/bootstrap-datepicker.css">
	<script src="vendors/bootstrap-datepicker/js/bootstrap-datepicker.js" type="text/javascript"></script>
    <script src="vendors/lightbox/ekko-lightbox.js" type="text/javascript"></script>
    <script src="js/bootstrap-select-1.11.2/dist/js/bootstrap-select.js"></script>
    <script src="js/typeahead/typeahead.bundle.js"></script>
    <script src="js/popcircle/jquery.easing.1.3.js"></script>
    <script src="js/popcircle/jquery.popcircle.1.0.js"></script>


	<!-- #################################################################### -->
    <link rel="stylesheet" type="text/css" href="js/summernote/summernote-bs4.css">
    <link href="js/ladda/ladda-themeless.min.css" rel="stylesheet">
<script src="js/slimscroll/jquery.slimscroll.js"></script>
<!-- SUMMERNOTE -->
<script src="js/summernote/summernote-bs4.js"></script>
<!-- Ladda -->
<script src="js/ladda/spin.min.js"></script>
<script src="js/ladda/ladda.min.js"></script>
<script src="js/ladda/ladda.jquery.min.js"></script>


<script language="javascript" src="js/AjaxUpload/AjaxUpload.2.0.min.js"></script>

<script src="js/jquery.cuenta.atras/jquery.cuenta.atras.js" type="text/javascript"></script>
    <script src="../../js/js_utiles_edusys.js"></script>
    

    <!-- Skycons -->
    <!--<script src="vendors/skycons/skycons.js"></script>-->
    <!-- Flot -->
 <!--   <script src="vendors/Flot/jquery.flot.js"></script>
    <script src="vendors/Flot/jquery.flot.pie.js"></script>
    <script src="vendors/Flot/jquery.flot.time.js"></script>
    <script src="vendors/Flot/jquery.flot.stack.js"></script>
    <script src="vendors/Flot/jquery.flot.resize.js"></script>-->
    <!-- Flot plugins -->
<!--    <script src="vendors/flot.orderbars/js/jquery.flot.orderBars.js"></script>
    <script src="vendors/flot-spline/js/jquery.flot.spline.min.js"></script>
    <script src="vendors/flot.curvedlines/curvedLines.js"></script>-->
    <!-- DateJS -->
    <!--<script src="vendors/DateJS/build/date.js"></script>-->
    <!-- JQVMap -->
 <!--   <script src="vendors/jqvmap/dist/jquery.vmap.js"></script>
    <script src="vendors/jqvmap/dist/maps/jquery.vmap.world.js"></script>
    <script src="vendors/jqvmap/examples/js/jquery.vmap.sampledata.js"></script>-->

    <!-- Custom Theme Scripts -->
    <script src="build/js/custom.min.js"></script>
     <style>
.form-control-plaintext {
    display: block;
    width: 100%;
    padding-top: .375rem;
    padding-bottom: .375rem;
    margin-bottom: 0;
    line-height: 1.5;
    background-color: transparent;
    border: solid transparent;
    border-width: 1px 0;
}
.mail-body {
    border-top: 1px solid #e7eaec;
    padding: 20px;
}
.mail-text {
    border-top: 1px solid #e7eaec;
}
.h-200 {
    min-height: 200px;
}
    .institucion-tooltip + .tooltip > .tooltip-inner {
        background-color: #b30004;
    }

	.institucion-tooltip + .tooltip > .tooltip-inner {background-color: #b30004;}
	.institucion-tooltip + .tooltip > .tooltip-arrow { border-bottom-color:#b30004; }
	.tooltip.top .tooltip-inner {
		background-color:#b30004;
	  }
	.tooltip.top .tooltip-arrow {
			  border-top-color: #b30004;
		   }
	.tooltip.right .tooltip-inner {
		background-color:#b30004;
	  }
	.tooltip.right .tooltip-arrow {
			  border-right-color: #b30004;
		   }
	.tooltip.bottom .tooltip-inner {
		background-color:#b30004;
	  }
	.tooltip.bottom .tooltip-arrow {
			  border-bottom-color: #b30004;
		   }  
	.tooltip.left .tooltip-inner {
		background-color:#b30004;
	  }
	.tooltip.left .tooltip-arrow {
			  border-left-color: #b30004;
	}      
	.nav_title{background:#b30004;}
	.modal-header{background:#b30004;}
	.left_col {background: #b30004; }
	.nav_title {background: #b30004; }
	body {  background: #b30004;}
	.nav.side-menu > li.active > a {
		text-shadow: rgba(0, 0, 0, 0.25) 0 -1px 0;
		background: linear-gradient(#eeb600, #ffc401), #b30004;
		box-shadow: rgba(0, 0, 0, 0.25) 0 1px 0, inset rgba(255, 255, 255, 0.16) 0 1px 0;
		color:#b30004;
	} 
	.sidebar-footer {background: #b30004; }
	.media .date {  background:#b30004;}
	.btn-default {  background: #b30004;}
	.btn-default:hover, .btn-default:focus, .btn-default:active, .btn-default.active, .open .dropdown-toggle.btn-default {background: #b30004;}  
	.login_content form input[type="text"]:focus, .login_content form input[type="email"]:focus, .login_content form input[type="password"]:focus { 
	border: 1px solid #b30004;  } 
	.daterangepicker.picker_3 table.table-condensed thead tr:first-child {	background: #b30004; }
	.daterangepicker td.available:hover, .daterangepicker th.available:hover {  background: #b30004;}
	.daterangepicker td.in-range {  color: #b30004;}
	.daterangepicker td.active, .daterangepicker td.active:hover {  color: #b30004; }
	</style>
   <!-- <script src="../10_funciones/js_utiles_edusysnet.js"></script>-->
	<script src="../../js/push.js/push.min.js"></script>
    <script>
 
    Push.create(':: EDUSYS - I.E.P. ALFONSO UGARTE ::', {
                            body: 'Bienvenido',
                            icon: '../../img/login/logo_edusys.png',
                            timeout: 4000,
                            onClick: function () {
                                console.log(":: EDUSYS - I.E.P. ALFONSO UGARTE ::"); 
                                window.focus();
                                this.close();
                            },
                            vibrate: [200, 100, 200, 100, 200, 100, 200]
                            }
        );
 
    </script>
 	<script>
function toggleFullScreen() {
	if ((document.fullScreenElement && document.fullScreenElement !== null) || (!document.mozFullScreen && !document.webkitIsFullScreen)) {
		if (document.documentElement.requestFullScreen) {
			document.documentElement.requestFullScreen();
		} else if (document.documentElement.mozRequestFullScreen) {
			document.documentElement.mozRequestFullScreen();
		} else if (document.documentElement.webkitRequestFullScreen) {
			document.documentElement.webkitRequestFullScreen(Element.ALLOW_KEYBOARD_INPUT);
		}
	} else {
		if (document.cancelFullScreen) {
			document.cancelFullScreen();
		} else if (document.mozCancelFullScreen) {
			document.mozCancelFullScreen();
		} else if (document.webkitCancelFullScreen) {
			document.webkitCancelFullScreen();
		}
	}
}
	 function f_load(url){

		 $.ajax({
			contentType: "application/x-www-form-urlencoded",
			url: url,
			type: "POST",
			success: function(datos){
				$("#div_main").html(datos);
			}

		});
	}
	var v_Patron=/[a-zA-Z0-9]/;
	
var states = ['1', '2', '3', '4', '5'];
var substringMatcher = function(strs) {
  return function findMatches(q, cb) {
    var matches, substringRegex;
	if (q === '') {
    	cb(states);
	}else{
    // an array that will be populated with substring matches
    matches = [];

    // regex used to determine if a string contains the substring `q`
    substrRegex = new RegExp(q, 'i');

    // iterate through the pool of strings and for any string that
    // contains the substring `q`, add it to the `matches` array
    $.each(strs, function(i, str) {
      if (substrRegex.test(str)) {
        matches.push(str);
      }
    });

    cb(matches);
	}
  };
};

function f_KillPPFF(){
	 
				 alert("Gracias por culminar la encuesta, la información brindada nos será de mucha utilidad");
				 location.reload(); 
	 
}


var generateRandom = function(){
	return (new Date().getTime()).toString().concat(Math.floor(Math.random()*33).toString());
};


$(document).ready(function(e) {

		var uploader = new AjaxUpload('#upload_button', {
				name: 'userfile',
				action: '../../modulos/m_tarea_linea/controler/file_tarea_linea_subir_edusys.php',
				data: {random:generateRandom(), action:'UPLOAD', folder:'tarea', prefix:'alumno'},
				onSubmit : function(file , ext){
					var pt = ".";

					if (uploader._input.files[0].size > 2097152){
					  new PNotify({
							title: 'Error, Peso de Documento!',
							text: 'Se encontr\u00F3 que supera los 2MB como m\u00E1ximo',
							type: 'error',
							styling: 'bootstrap3',
							before_open: function (pnotify) {
								$(".ui-pnotify").css("z-index", 1000410);
							}
					  });
					  $('#restar_adjunto').val("");
					  return false;
					}
					if(!(file && (file.split(pt).length) == 2)){
						new PNotify({
							title: 'Error, Nombre de Documento!',
							text: 'Se encontr\u00F3 que hay un punto en el nombre',
							type: 'error',
							styling: 'bootstrap3',
							before_open: function (pnotify) {
								$(".ui-pnotify").css("z-index", 1000410);
							}
						});
						return false;
					}
					if(!(file && ((file.split(pt)[0]).length) < 111)){
						new PNotify({
							title: 'Error, Nombre de Documento!',
							text: 'El nombre del Documento es muy largo',
							type: 'error',
							styling: 'bootstrap3',
							before_open: function (pnotify) {
								$(".ui-pnotify").css("z-index", 1000410);
							}
						});
						return false;
					}
					if(!(/^[0-9a-zA-Z\.\-\_]+$/.test(file))){
						new PNotify({
							title: 'Error, Nombre de Documento!',
							text: 'S\u00F3lo se admiten documentos con n\u00FAmeros, letras, gui\u00F3n, raya abajo y nada m\u00E1s',
							type: 'error',
							styling: 'bootstrap3',
							before_open: function (pnotify) {
								$(".ui-pnotify").css("z-index", 1000410);
							}
						});
						$('#restar_adjunto').val("");
						return false;
					}
					if (! (ext && /^(pdf|doc|xls|ppt|docx|xlsx|pptx|txt|jpg)$/.test(ext.toLowerCase()))){
						new PNotify({
							title: 'Error, Documento Seleccionado!',
							text: 'S\u00F3lo se admiten documentos ".doc, .pdf, .ppt, .xls, .txt, .doc, .docx, .jpg',
							type: 'error',
							styling: 'bootstrap3',
							before_open: function (pnotify) {
								$(".ui-pnotify").css("z-index", 1000410);
							}
						});
						$('#restar_adjunto').val("");
						return false;
					} else {
						$('#restar_adjunto').val(file);
						this.disable();
					}
					$('.show-attach').hide();
					$('.show-progress').show();

					var stops = [25, 55, 85, 100];
					$.each(stops, function(index, value){
						setTimeout(function(){
							$( ".progress-bar").css("width", value + "%").attr("aria-valuenow", value );
							$( ".progress-bar span i").html(value + "%");
						}, index * 1500);
					});

				},

				onComplete: function(file, response){
					this.enable();
					$('.show-attach').show();
					$('.show-progress').hide();
					var p = ($.trim(response));
					if(p == "peso"){
						new PNotify({
							title: 'Error, Documento Peso!',
							text: "El documento excede la capacidad permitida 2MB",
							type: 'error',
							styling: 'bootstrap3',
							before_open: function (pnotify) {
								$(".ui-pnotify").css("z-index", 1000410);
							}
						});
					}else{
						var punto = ".";
						var arr = p.split("|");
						var estado = arr[0];
						var nuevo = $.trim(arr[1]);
						var original = $.trim(arr[2]);
						var formato = arr[3];
						var fecattins = $.trim(arr[4]);
						var configroute = parseInt($.trim(arr[5]));
						if(estado == "ok"){

							new PNotify({
								title: 'Info!',
								text: "El documento fue cargado correctamente",
								type: 'success',
								styling: 'bootstrap3',
								before_open: function (pnotify) {
									$(".ui-pnotify").css("z-index", 1000410);
								}
							});

							var tt = $('#restar_adjunto');

							tt.val(nuevo + punto + formato);
							tt.attr("adjunto", nuevo + punto + formato);
							tt.attr("adjuntor", original + punto + formato);
                            tt.attr("fecattins", fecattins);
							if(configroute > 0){
								var dxpathreal = $.trim(arr[6]);
								var dxid = $.trim(arr[7]);
								var dxclim = $.trim(arr[8]);
								tt.attr("dxpathreal", dxpathreal);
								tt.attr("dxid", dxid);
								tt.attr("dxclim", dxclim);
							}
						}else{
							$('#restar_adjunto').val("");
						}
					}

				}
		});
		$(".css-btn-send-respuesta-tarea").click(function(e) {
			var v_adjunto	=	$("#restar_adjunto");




			var v_sectarlin	=	$("#datos_tarea").attr("sectarlin");
			var v_secmat	=	$("#datos_tarea").attr("secmat");
			var v_codalu	=	$("#datos_tarea").attr("codalu");
			var v_contenido = $('.css-summernote-tarea').summernote('code');
			var v_ban		=	0;

			if(v_adjunto.val() == ""){
				v_adjunto.closest('.form-group').addClass('has-error');
				v_ban++;
			}else{
				v_adjunto.closest('.form-group').removeClass('has-error');
			}

			if(v_ban != 0){
				new PNotify({
					title: 'Error!',
					text: 'Seleccione el documento a adjuntar',
					type: 'error',
					styling: 'bootstrap3',
					before_open: function (pnotify) {
						$(".ui-pnotify").css("z-index", 1000410);
					}
				});

				return false;
			}



			$(".css-btn-send-respuesta-tarea").attr('disabled','disabled');
			$.ajax({
				contentType: "application/x-www-form-urlencoded",
				url: "tareas_linea_edusys.php",
				data: "submit=100&sectarlin="+v_sectarlin+"&secmat="+v_secmat+"&codalu="+v_codalu+"&contenido="+v_contenido,
				type: "POST",
				success: function(datos){
					var v_secrestarlin = $.trim(datos);
					$.ajax({
							contentType: "application/x-www-form-urlencoded",
							url: "../../modulos/m_tarea_linea/controler/file_tarea_linea_subir_edusys.php",
							type: "POST",
							data: "random="+generateRandom()+"&submit=2222871&take=ins&filetracing=1&secrestarlin="+v_secrestarlin+"&sectarlin="+v_sectarlin+"&adjunto="+(v_adjunto.attr("adjunto")?$.trim(v_adjunto.attr("adjunto")):"")+"&adjuntor="+(v_adjunto.attr("adjuntor")?$.trim(v_adjunto.attr("adjuntor")):"")+ "&fecattins=" + (v_adjunto.attr("fecattins")?$.trim(v_adjunto.attr("fecattins")):"") + "&dxpathreal=" + (v_adjunto.attr("dxpathreal")?$.trim(v_adjunto.attr("dxpathreal")):"") + "&dxid=" + (v_adjunto.attr("dxid")?$.trim(v_adjunto.attr("dxid")):"") + "&dxclim=" + (v_adjunto.attr("dxclim")?$.trim(v_adjunto.attr("dxclim")):""),
							success: function(datos){
								new PNotify({
									title: 'Alerta!',
									text: 'Respuesta envida correctamente',
									type: 'success',
									styling: 'bootstrap3',
									before_open: function (pnotify) {
										$(".ui-pnotify").css("z-index", 1000410);
									}
								});
								$("#myModal-ViewTarea").modal('hide');
								 $("#restar_para").val("");
								 $("#restar_asunto").val("");
								 $("#restar_curso").val("");
								 $("#datos_tarea").attr("sectarlin",0);
								$(".css-btn-send-respuesta-tarea").removeAttr('disabled');
								f_load("tareas_linea_edusys.php");

							}
					});
				}
			});
		});
		$('.css-summernote-tarea').summernote({
			focus: true,
			height: 180,
			toolbar: [
			// [groupName, [list of button]]
			//['style', ['bold', 'italic', 'underline', 'clear']],
			['style', ['bold', 'italic', 'underline']],
			//['font', ['strikethrough', 'superscript', 'subscript']],
			['fontsize', ['fontsize']],
			['color', ['color']]
			//['para', ['ul', 'ol', 'paragraph']],
			//['height', ['height']],
			]
		});

	});


	$(document).ready(function(e) {
		 $(".css_cerrar_sistema").click(function(e) {
            location.href="../../modulos/inludes/salir_session.php";
        });
				 	$(".css_li_hermanos").click(function(e) {
        var v_codalu	=	$(this).attr("codalu");
		var v_secmat	=	$(this).attr("secmat");
		var v_urlfot	=	$(this).attr("urlfot");
		var v_nomalu	=	$(this).attr("nomalu");
		
		$.ajax({
			contentType: "application/x-www-form-urlencoded",
			url: "f_mov_alumnos_edusys.php",
			type: "POST",
			data: "submit=&opt=3&codalu="+v_codalu+"&secmat="+v_secmat+"&urlfot="+v_urlfot,
			success: function(datos){
				var v_datos 	=	datos;
				var v_arrdat	=	v_datos.split("*");
				$("#img_familia").attr("src",v_urlfot);	 
				$("#img_perfil").attr("src",v_urlfot);	 
				$("#span_nomperfil").text(v_nomalu);
				
				var v_url		=	v_arrdat[0];
				if(v_url == "" || v_url  == null){
					f_load("main_edusys.php");
				}else{
					f_load(v_url);
				}
				
				var v_stdenc	=	v_arrdat[1];
				if(parseInt(v_stdenc,10) == 1){
					location.reload();
				}
				 
			}
		});
		
    });
	 	 
	$(".css_txt_encuesta").keypress(function(e) {
        if( ( /\d/.test(String.fromCharCode(event.which))) || event.which==8 || event.which == 119 || event.which == 222 || event.which == 13) {
				//if (event.which == 13) {f_login_edusysnet();} 
				return true;
			}else{return false;} 
    }).keyup(function(e) {//blur
        var v_max		=	$(this).attr("max");
		var v_min		=	$(this).attr("min");
		var v_fila		=	$(this).attr("fila");
		var v_columna	=	$(this).attr("columna");
		
		var v_totpre	=	$(this).attr("totpre");
		var v_totpro	=	$(this).attr("totpro");
		
		var v_profesor	=	$(this).attr("profesor");
		var v_curso		=	$(this).attr("curso");
		var v_despreenc	=	$(this).attr("despreenc");
		var v_value		=	$(this).val();
		


		if(v_value != ""){
			if(v_value >= v_min && v_value <= v_max){ 
				var v_columna_nex	=	(parseInt(v_columna,10)+1);
				var v_fila_nex		=	(parseInt(v_fila,10)+1);
				//alert(v_columna_nex+"/"+v_fila_nex);
				
					if(v_columna_nex <= v_totpro){
						$(".css_input_"+v_fila+"_"+v_columna_nex).focus();
					}else{
						$(".css_input_"+v_fila_nex+"_1").focus();	
					}
			}else{
				new PNotify({
				title: 'Error,Dato no valido!',
				text: 'Pregunta: '+v_despreenc+'<br>Profesor:'+v_profesor+'<br>Curso:'+v_curso,
				type: 'error',
				styling: 'bootstrap3',
				
				//addclass: "stack-bar-top",
				//cornerclass: "",
				//width: "100%",
				
				before_open: function(pnotify) {
					$(".ui-pnotify").css("z-index", 1000410);  
                }
			});
				$(this).val("");
				return false;
			}	
		}
    });/*.keyup(function(e) {
        var v_max		=	$(this).attr("max");
		var v_min		=	$(this).attr("min");
		var v_fila		=	$(this).attr("fila");
		var v_columna	=	$(this).attr("columna");
		
		var v_totpre	=	$(this).attr("totpre");
		var v_totpro	=	$(this).attr("totpro");
		
		var v_profesor	=	$(this).attr("profesor");
		var v_curso		=	$(this).attr("curso");
		var v_despreenc	=	$(this).attr("despreenc");
		var v_value		=	$(this).val();
		
		if(v_value != ""){
			if(v_value >= v_min && v_value <= v_max){ 
				var v_columna_nex=(v_columna+1);
					if(v_columna_nex <= v_totpro){
						$(".css_input_"+v_fila+"_"+v_columna_nex).focus().select();
					}else{
						$(".css_input_"+(v_fila+1)+"_1").focus().select();	
					}
			}else{
				new PNotify({
				title: 'Error,Dato no valido!',
				text: 'Pregunta: '+v_despreenc+'<br>Profesor:'+v_profesor+'<br>Curso:'+v_curso,
				type: 'error',
				styling: 'bootstrap3',
				before_open: function(pnotify) {
					$(".ui-pnotify").css("z-index", 1000410); 
                        
                }
			});
				$(this).val("");
				return false;
			}	
		}
    });*/
	
	$(".delete_stickynote").click(function(e) {
		var padre	=	$(this).parent().parent();
		padre.remove();
	});
	$(".note_common").click(function(e) {
        var v_index=99999999;
		
		$(".note_common").css({"z-index":99999999});
		$(this).css({"z-index":999999999});
    });
	$('.css_password').attr('value','');
	$('.css_password').keypress(function(event) {
		if( ( v_Patron.test(String.fromCharCode(event.which))) || event.which==8 || event.which == 119 || event.which == 222 || event.which == 13) {
			return true;
		}else{return false;}

	});
$("#form_change_password") .validate({
	event: "blur",
	rules: {//
		'password_original': "required",
		//'password_chage': "required",
		//'password_chage_conf': "required" ,
		'password_chage': {
			required: true,
			minlength: 6,
			maxlength: 10
		} ,
		'password_chage_conf': {
			equalTo: "#password_chage",
			minlength: 6,
			maxlength: 10
		}
	},
	messages: {
		'password_original': "&nbsp;",
		'password_chage': "&nbsp;",
		'password_chage_conf': "&nbsp;"
	},
	highlight: function(element) {
        $(element).closest('.form-group').addClass('has-error');
    },
	unhighlight: function(element) {
         $(element).closest('.form-group').removeClass('has-error');
    },
	//errorElement: 'span',
    //errorClass: 'help-block',
	errorPlacement: function(error, element) {
		if(element.parent('.input-group').length) {
			error.insertAfter(element.parent());
		} else {
			error.insertAfter(element);
		}
	},
	submitHandler: function(form){
		$( "#cmb_change_password" ).children().show();
		$.ajax({
			contentType: "application/x-www-form-urlencoded",
			url: "f_mov_alumnos_edusys.php",
			type: "POST",
			data: "submit=&opt=2&codalu=20142351&password_original="+$("#password_original").val()
				+"&password_chage="+$("#password_chage").val()
				+"&password_chage_conf="+$("#password_chage_conf").val(),
			success: function(datos){
					if(datos == 1){
				 	 	$('#div_modal_change_password').modal('hide');
				  		$( "#cmb_change_password" ).children().hide();
						alert("ContraseÃƒÂ±a actualizada corretamente, por favor vuelva a iniciar session.");
						location.href="../15_template/index.php?op=termsession";
					}else{
						$('.css_password').val('');
					}
			}
		});
	},
	success: function(element) {
		$(element).closest('.form-group').removeClass('has-error').addClass('has-success');
 	  	$(element).addClass('hide');
	}
});

		$(".toggle-fullscreen").click(function(e) {
            toggleFullScreen();
        }).css({"cursor":"pointer"});
	new showLocalTime("timecontainer", "server-php", 0, "short");

		f_load("main_edusys.php");
		$(".css_li_menu").click(function(e) {
			$(".css_li_menu").removeClass( "active" );
            f_load($(this).attr("url"));
			$(this).addClass( "active" );
			//var li = $( this ).closest();
			//li.addClass( "active" );
			/*$(".css_li_menu").each(function(index, element) {
                
            });*/
			//active';}?> css_li_menu
     }).css({"cursor":"pointer"});
		/*
		$(".css_ruta").click(function(e) {
			$(".css_li_menu").removeClass( "active" );
            f_load($(this).attr("url")); 
        }).css({"cursor":"pointer"});
		*/
    });
	</script>

  </body>
</html>
