# Java Bundle GNUStep
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html><head lang="en">
    <link href="README_files/bootstrap.min.css" rel="stylesheet">
    <link href="README_files/bs-theme-gnustep.css" rel="stylesheet">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="Content-type" content="text/html; charset=UTF-8">
    <link rel="SHORTCUT ICON" href="https://gnustep.github.io/images/gnustep-favicon.ico">
  </head>
	  <body>
	  
    <nav class="navbar navbar-inverse" role="navigation">
      <!-- Brand and toggle get grouped for better mobile display -->
      <div class="navbar-header">
	<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
	  <span class="sr-only">Toggle navigation</span>
	  <span class="icon-bar"></span>
	  <span class="icon-bar"></span>
	  <span class="icon-bar"></span>
	</button>
	<div class="navbar-brand"><img src="README_files/GNUstepLogo_Square.png" alt="GS logo"></div>
      </div>
      
      <!-- Collect the nav links, forms, and other content for toggling -->
      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
	<ul class="nav navbar-nav">
	  <li class="dropdown">
	    <a href="#" class="dropdown-toggle" data-toggle="dropdown">For Users<span class="caret"></span></a>
	    <ul class="dropdown-menu">
	      <li><a href="https://gnustep.github.io/information/aboutGNUstep.html">Introduction</a></li>
	      <li><a href="https://gnustep.github.io/experience/apps.html">Applications</a></li>
              <li><a href="https://gnustep.github.io/resources/sources.html">Download</a></li>
              <li><a href="http://wiki.gnustep.org/index.php/User_Guides">User Guides</a></li>
              <li><a href="http://wiki.gnustep.org/index.php/Get_Help">Get Help</a></li>
	    </ul>
	  </li>
	  
	  <li class="dropdown">
	    <a href="#" data-toggle="dropdown">For Developers<span class="caret"></span></a>
	    <ul class="dropdown-menu">
              <li><a href="https://gnustep.github.io/experience/DeveloperTools.html">App Development Tools</a></li>
              <li><a href="https://gnustep.github.io/developers/documentation.html">GNUstep Documentation</a></li>
	      <li><a href="https://gnustep.github.io/developers/index.html">Improve GNUstep</a></li>
	      <li><a href="http://wiki.gnustep.org/index.php/Blogs">Developer Blogs</a></li>
	    </ul>
	    
	  </li>
	  <li class="dropdown">
	    <a href="#" role="button" data-toggle="dropdown">External<span class="caret"></span></a>
	    <ul class="dropdown-menu">
	      <li><a href="http://github.com/gnustep/">Main Development (Github)</a><br>
              </li><li><a href="http://wiki.gnustep.org/">Project Wiki</a></li>
	      <li><a href="https://gnustep.github.io/information/gethelp.html">Mailing Lists</a></li>
              <!-- li><a href="http://wiki.gnustep.org/index.php/GNUstepWiki:Site_support">Donations</a></li -->
	    </ul>
	  </li>
	  
	</ul>

        <ul class="nav navbar-nav navbar-right">
	  <li><a href="http://wiki.gnustep.org/index.php/Report_Bugs">Report Bugs</a></li>
        </ul>

      </div>
    </nav>

    <div class="jumbotron">
      <div class="container">
        <h2>GNUstep Overview</h2>
	<p>GNUstep is a mature Framework, suited both for advanced GUI desktop 
applications as well as server applications. The framework closely 
follows Apple's Cocoa (formerly NeXT's OpenStep) APIs but is portable to
 a variety of platforms and architectures.</p>
	<p>Read more about the <a href="https://gnustep.github.io/information/aboutGNUstep.html">GNUstep project</a>, or the  <a href="https://gnustep.github.io/developers/whoiswho.html">people</a> behind it.</p>
	<p>GNUstep offers Development tools for command-line and GUI development, as well as the foundations for a Desktop environment.
	</p>
      </div>
    </div>
<!--   users  carrousel -->
    <section>
        <div class="container">
          <div class="row">
            <div class="col-md-4 mt32 mb32">
              <h2>Users</h2>
              <h4 class="text-primary">Attractive applications</h4>
              <!-- p><strong>Our <a href="#">User page on the wiki</a> contains help, application list, themes and icons.</strong></p -->
              <p>
                <i class="fa fa-info-circle fa-1x text-primary"></i><!--icon-->
                <strong class="text-primary">Application packages are mostly available from your Linux or BSD distribution repository</strong>
              </p>
            </div>
            <div class="col-md-8 carousel slide mt32 mb32" data-interval="10000" id="usersCarrousel" style="height: 600px;">
              <div class="carousel-inner">
                <div class="item active">
                  <img alt="GNUMail is a fully featured desktop email application running on Linux (or FreeBSD, OpenBSD, etc) and Apple Mac OS X" class="img img-responsive" src="README_files/GNUMail_1-2.png" height="600">
                  <div class="carousel-caption">
                    <p class="bg-primary"><strong>GNUMail</strong> is a powerful email application</p>
                  </div>
                </div>
                <div class="item">
                  <img alt="GWorkspace is a desktop and files manager application running on Linux (or FreeBSD, OpenBSD, etc) and Apple Mac OS X" class="img img-responsive" src="README_files/GWorkspace.jpg" height="600">
                  <div class="carousel-caption">
                    <p class="bg-primary"><strong>GWorkspace</strong> is more than a file manager</p>
                  </div>
                </div>
                <div class="item">
                  <img alt="ProjectCenter is an advanced IDE running on Linux (or FreeBSD, OpenBSD, etc) and Apple Mac OS X" class="img img-responsive" src="README_files/ProjectCenter-0.27.png" height="600">
                  <div class="carousel-caption">
                    <p class="bg-primary"><strong>ProjectCenter</strong> is an IDE for Objective-C</p>
                  </div>
                </div>
              </div>
              <div class="carousel-control left" href="#usersCarrousel" data-slide="prev" role="button">
                 <span class="icon-prev  bg-primary" aria-hidden="true"></span>
                 <span class="sr-only">Previous</span>
               </div>
              <div class="carousel-control right" href="#usersCarrousel" data-slide="next" role="button">
                <span class="icon-next bg-primary" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </div>
<!--              <ol class="carousel-indicators">
                <li class="active bg-primary" data-slide-to="0" data-target="#usersCarrousel"></li>
                <li data-slide-to="1" data-target="#usersCarrousel" class=" bg-primary"></li>
                <li data-slide-to="2" data-target="#usersCarrousel" class=" bg-primary"></li>
              </ol>-->
            </div>
          </div>
        </div>
      </section>
<!--/users carrousel-->


    <div class="container">
        <h2>Developers</h2>
        <div class="container">
          <h3 class="page-header">Automated Installation</h3>
	  The command to download GNUstep and build its libraries from source is:
	    <br><code>curl https://raw.githubusercontent.com/gnustep/tools-scripts/master/gnustep-web-install-dev | bash</code>
	    <br><br>This script may not support installation on all operating systems.  Let us know if it doesn't work on your system.
        <h3 class="page-header">Experience</h3>
        <div class="img-thumbnail floatright"> <a href="https://gnustep.github.io/images/ftp_sleek.png"><img src="README_files/ftp_sleek-crop.jpg" alt="Menu Screenshot"></a> </div>
        
        <p>GNUstep provides the foundations for a portable desktop environment,
            but delegates this task to other projects, like:</p>
        <ul>
        <li><a href="http://www.nongnu.org/gap/">The GNUstep Application Project</a></li>
        <li><a href="https://github.com/trunkmaster/nextspace">NEXTSPACE</a></li>
        <li><a href="http://www.etoile-project.org/">Etoile</a></li>
        </ul>
        <p><b>More?</b> </p>
        <div style="margin-left: 20px;">
            About our user <a href="https://gnustep.github.io/experience/apps.html">Experience</a><br>
            A comprehensive list of applications on our  <!-- <a href="http://wiki.gnustep.org/index.php/Category:Applications">Wiki
            application pages</a> and in the --> <a href="http://www.gnustep.org/softwareindex/">Software Index</a><br>
            <br>
        </div>
        </div>

        <div class="container">
        <h3 class="page-header">Develop!</h3>
        <div class="img-thumbnail floatright"> <a href="https://gnustep.github.io/images/full-screenshot1.png"><img src="README_files/screenshot1.png" alt="Menu Screenshot"></a> </div>
        <p>GNUstep provides an environment to easily develop
            advanced GUI desktop applications as well as server applications.</p>
        <p> GNUstep's core framework provides open source version of the
 Cocoa's (formerly known as OpenStep from NeXT) APIs and tools for as 
many platforms as possible. <br>
            GNUstep provides a robust implementation of the AppKit and
            Foundation libraries as well as the  <a href="https://gnustep.github.io/experience/DeveloperTools.html">development tools</a>
            including the advanced interface designer <a href="https://gnustep.github.io/experience/Gorm.html">Gorm</a> (the InterfaceBuilder) and the IDE 
            <a href="https://gnustep.github.io/experience/ProjectCenter.html">ProjectCenter</a> (ProjectBuilder/Xcode).<br>
        Thematic instead provides a user-friendly access to <a href="https://gnustep.github.io/experience/Theming.html">theming</a>.
        </p>
        <p>GNUstep seeks to be source code compatible with Cocoa, it can
            thus be used to develop and build cross-platform 
applications
            between Macintosh (Cocoa),  Unix (Solaris) and Unix-like 
(GNU/Linux and GNU/Hurd, NetBSD, OpenBSD, FreeBSD) platforms as well as <a href="https://gnustep.github.io/windows/index.html">Windows</a>
            <br>
            GNUstep's main development language is Objective-C, but
            GNUstep is not limited to that. </p>
        <p><b>More?</b> </p>
        <div style="margin-left: 20px;"> 
            About <a href="https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html#//apple_ref/doc/uid/TP40011210">Objective-C 2.0</a> 
            <br>
            <!--
                Need help building from source code? Look at our <a href="http://wiki.gnustep.org/index.php/User_Guides">Guides</a>.
                -->
        </div>
        </div>
        
        <div class="container">
        <h3 class="page-header">Get it!</h3>
        <ul>
            <li><b>
                <a href="https://gnustep.github.io/resources/downloads.html">Download page</a>: Our stable packages, for developers users and packagers.</b></li><b>
            </b><li><b>On <a href="https://gnustep.github.io/windows/index.html">Windows</a>, use the dedicated <a href="https://gnustep.github.io/windows/installer.html">installer</a> to get started.
            </b></li>
            <li><b>
                <a href="https://gnustep.github.io/resources/sources.html">Source download page</a>:
                More selection and daily snapshots
            </b></li>
            <li><b><a href="https://github.com/gnustep/">From GIT</a>: Access our Source repository (currently on Github)</b></li>
        </ul>
        </div> <!-- container -->
    </div>
  

</body></html>
