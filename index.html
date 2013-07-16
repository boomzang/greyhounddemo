<!doctype html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="apple-mobile-web-app-capable" content="yes" />
        
        <title>Epcot Connection</title>
        
        
        
        <!-- iPhone Styles -->
        <link rel="stylesheet" media="all and (max-device-width: 480px) and (orientation:portrait)" href="themes/disney/iphone.css">
        
        <!-- iPhone Landscape -->
        <link rel="stylesheet" media="all and (max-device-width: 480px) and (orientation:landscape)" href="themes/disney/iphone-landscape.css"> 
        
        <!-- iPad Portrait Styles -->
        <link rel="stylesheet" media="all and (min-device-width: 481px) and (max-device-width: 1024px) and (orientation:portrait)" href="themes/disney/ipad-portrait.css"> 
        
        <!-- ipad Landscape Styles -->
        <link rel="stylesheet" media="all and (min-device-width: 481px) and (max-device-width: 1024px) and (orientation:landscape)" href="themes/disney/ipad-landscape.css">
        
        <!-- Default Styles -->
        <link rel="stylesheet" type="text/css" href="scripts/jqtouch/jqtouch.css"/>
        <link rel="stylesheet" media="all and (min-device-width: 1025px)" href="themes/disney/ipad-landscape.css">
        
        <link rel="stylesheet" href="styles/main.css"/>
        <script src="scripts/jquery.1.4.2.js" type="text/javascript" charset="utf-8"></script>
        <script src="scripts/jqtouch/jqtouch.js" type="application/x-javascript" charset="utf-8"></script>
        
        <style type="text/css" media="screen">@import "scripts/extensions/jqt.photo.css";</style>
		<script src="scripts/extensions/jqt.photo.js" type="application/x-javascript" charset="utf-8"></script>

		<script type="text/javascript" src="scripts/jplayer/jquery.jplayer.min.js"></script>
        <script type="text/javascript" src="scripts/jplayer/jplayer.playlist.min.js"></script>
        
        <!-- Clock -->
        <link type="text/css" rel="stylesheet" href="scripts/clock/style.css"/>

        <script type="text/javascript" charset="utf-8">
            var jQT = new $.jQTouch({
                icon: 'icon.png',
                addGlossToIcon: false,
                startupScreen: 'startup.png',
                statusBar: 'black',
				preloadImages: [
					'themes/disney/img/activeButton.png',
					'themes/disney/img/back_button.png',
					'themes/disney/img/back_button_clicked.png',
					'themes/disney/img/blueButton.png',
					'themes/disney/img/button.png',
					'themes/disney/img/button_clicked.png',
					'themes/disney/img/grayButton.png',
					'themes/disney/img/greenButton.png',
					'themes/disney/img/redButton.png',
					'themes/disney/img/whiteButton.png',
					'themes/disney/img/loading.gif'
					]
            });
			
		
			$(function(){
				
				//Photo Gallery
				jQT.generateGallery("gallery",[
					<?php
						
						$directory = 'images/gallery';	//where the gallery images are located
						$allowed_types=array('jpg','jpeg','gif','png');	//allowed image types
						$file_parts=array();
						$ext='';
						$title='';
						$count = 0;
						//try to open the directory
						$dir_handle = @opendir($directory) or die("There is an error with your image directory!");
						$filecount = count(glob($directory ."*.jpg"));
						while ($file = readdir($dir_handle))	//traverse through the files
						{
							if($file=='.' || $file == '..') continue;
							$file_parts = explode('.',$file);	//split the file name and put each part in an array
							$ext = strtolower(array_pop($file_parts));	//the last element is the extension
						
							$title = implode('.',$file_parts);	//once the extension has been popped out, all that is left is the file name
							$title = htmlspecialchars($title);	//make the filename html-safe to prevent potential security issues
						
							$nomargin='';
							if(in_array($ext,$allowed_types))	//if the extension is an allowable type
							{
								echo '
									{src:"'.$directory.'/'.$file.'"},
								';
							}
						}
						closedir($dir_handle);	//close the directory
					?>
					],
					{backLink:'<a class="back" href="#">Back</a>'});
					
				// Music Player
				new jPlayerPlaylist({
					jPlayer: "#jquery_jplayer_1",
					cssSelectorAncestor: "#jp_container_1"
				}, [
					{
						title:"It's a Small World",
						mp3:"music/smallworld.mp3",
					},
					{
						title:"When You Wish Upon a Star",
						mp3:"music/wish_star.mp3",
					},
					{
						title:"When the Night Has Come",
						mp3:"music/when_the_night.mp3",
					},
				], {
			
					swfPath: "scripts/jplayer",
					supplied: "mp3"
				});
				
				//Video Player
				new jPlayerPlaylist({
					jPlayer: "#jquery_jplayer_2",
					cssSelectorAncestor: "#jp_container_2"
				}, [
					{
						title:"Hayaku",
						m4v: "movies/hayaku.mp4",
						poster:"images/movies/hayaku.jpg"
					},
					{
						title:"KI: Michael Levin",
						m4v: "movies/ki.mp4",
						poster: "images/movies/ki.jpg"
					},
					{
						title:"Tytan Demo Reel",
						m4v: "movies/tytanreel.mp4",
						poster: "images/movies/tytanreel.jpg"
					}
				], {
					swfPath: "scripts/jplayer",
					supplied: "m4v",
					sizeFull:{width:"100%",height:"100%"}
				});
				
				$('video').attr("controls","controls")
					
				//Clock	
				setInterval( function() {
				  var seconds = new Date().getSeconds();
				  var sdegree = seconds * 6;
				  var srotate = "rotate(" + sdegree + "deg)";
				  
				  $("#sec").css({"-moz-transform" : srotate, "-webkit-transform" : srotate});
					  
				  }, 1000 );
				  
			 
				  setInterval( function() {
				  var hours = new Date().getHours();
				  var mins = new Date().getMinutes();
				  var hdegree = hours * 30 + (mins / 2);
				  var hrotate = "rotate(" + hdegree + "deg)";
				  
				  $("#hour").css({"-moz-transform" : hrotate, "-webkit-transform" : hrotate});
					  
				  }, 1000 );
			
			
				  setInterval( function() {
				  var mins = new Date().getMinutes();
				  var mdegree = mins * 6;
				  var mrotate = "rotate(" + mdegree + "deg)";
				  
				  $("#min").css({"-moz-transform" : mrotate, "-webkit-transform" : mrotate});
					  
				  }, 1000 );
					
				//Fade In Animation	
				setInterval( function() {
									  
				  $("#mapnav").fadeIn("slow");
					  
				  }, 500 );
				  
				  setInterval( function() {
									  
				  $("#attnav").fadeIn("slow");
					  
				  }, 1000 );
				  
				  setInterval( function() {
									  
				  $("#dinnav").fadeIn("slow");
					  
				  }, 1500 );
				  
				  setInterval( function() {
									  
				  $("#gamnav").fadeIn("slow");
					  
				  }, 2000 );
				  
				  setInterval( function() {
									  
				  $("#fastnav").fadeIn("slow");
					  
				  }, 2500 );
				
				
			});
			
			
        </script>
        
       

        <style type="text/css" media="screen">

        </style>
    </head>
    <body>
        <div id="jqt">
<!-- ----------------------------------------------------------------- Content Area ----------------------------------------------------- -->
<!-- Home Page -->
            <div id="home" class="current">
                <div id="headerimage"></div>
                	
                <ul id="phonenav" class="rounded">
                    <li class="arrow"><a href="#map" onClick="setTimeout(function(){mapscroller.refresh()},100);">Map</a></li>
                    <li class="arrow"><a href="#attractions">Attractions</a></li>
                    <li class="arrow"><a href="#dining">Dining</a></li>
                    <li class="arrow"><a href="#games">Games</a></li>
                    <li class="arrow"><a href="#fastpass">Fast Pass</a></li>
                    <li class="arrow"><a href="#movies">Videos</a></li>
                    <li class="arrow"><a href="#music">Music Player</a></li>
                </ul>
                
                <ul class="ipadhomenav clearfix">
                    <li id="mapnav"><a href="#map" class="ipadnavimg" style="background-position:0px 0px !important;">Map</a></li>
                    <li id="attnav"><a href="#attractions" class="ipadnavimg" style="background-position:-141px 0px !important;">Attractions</a></li>
                    <li id="dinnav"><a href="#dining" class="ipadnavimg" style="background-position:-282px 0px !important;">Dining</a></li>
                    <li id="gamnav"><a href="#games" class="ipadnavimg" style="background-position:-423px 0px !important;">Games</a></li>
                    <li id="fastnav"><a href="#fastpass" class="ipadnavimg" style="background-position:-564px 0px !important;">Fast Pass</a></li>
                </ul>
                
                <ul id="clock">	
                    <li id="reflection"></li>
                    <li id="sec"></li>
                    <li id="hour"></li>
                    <li id="min"></li>
                </ul>
                
                <a href="#music" class="whiteButton" id="musicplayeripad">Music Player</a>
				<a href="#movies" class="whiteButton" id="videosipad">Videos</a>
                                
                <div id="footerimage"></div>
            </div>

                        
<!-- Map Page -->       
                <div id="map">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                   	<div class="section_header maphead"></div>
                	<div class="section_name"><span>Park Map</span></div>
                    
                    <img src="images/map.jpg" border="0" align="left" width="100%"/>
                    
                </div>
            
<!-- Attractions Page -->       
                <div id="attractions">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                   	<div class="section_header attractionhead"></div>
                	<div class="section_name"><span>Attractions</span></div>
                    
                    <ul class="rounded">
                        <li class="arrow"><a href="#american">American Adventure Pavilion</a></li>
                        <li class="arrow"><a href="#">Canada Pavilion</a></li>
                        <li class="arrow"><a href="#">Captain EO</a></li>
                        <li class="arrow"><a href="#">China Pavilion</a></li>
                        <li class="arrow"><a href="#">Circle of Life</a></li>
                        <li class="arrow"><a href="#">Disney's Kim Possible World Showcase Adventure</a></li>
                        <li class="arrow"><a href="#">Ellen's Energy Adventure</a></li>
                        <li class="arrow"><a href="#">France Pavilion</a></li>
                        <li class="arrow"><a href="#">Germany Pavilion</a></li>
                        <li class="arrow"><a href="#">Gran Fiesta Tour Starring the Three Caballeros</a></li>
                        <li class="arrow"><a href="#">ImageWorks</a></li>
                        <li class="arrow"><a href="#">Imagination! Pavilion</a></li>
                        <li class="arrow"><a href="#">Impressions de France</a></li>
                        <li class="arrow"><a href="#">Innoventions</a></li>
                        <li class="arrow"><a href="#">Italy Pavilion</a></li>
                        <li class="arrow"><a href="#">Japan Pavilion</a></li>
                        <li class="arrow"><a href="#">Journey Into Imagination With Figment</a></li>
                        <li class="arrow"><a href="#">Living with the Land</a></li>
                        <li class="arrow"><a href="#">Maelstrom</a></li>
                        <li class="arrow"><a href="#">Mexico Pavilion</a></li>
                        <li class="arrow"><a href="#">Mission: SPACE Advanced Training Lab</a></li>
                        <li class="arrow"><a href="#">Mission: SPACE Pavilion</a></li>
                        <li class="arrow"><a href="#">Mission: SPACE®</a></li>
                        <li class="arrow"><a href="#">Morocco Pavilion</a></li>
                        <li class="arrow"><a href="#">National Treasures</a></li>
                    </ul>
                </div>
                
<!-- American Adventure Pavilion Page -->       
                <div id="american">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                    <div class="section_header attractionhead"></div>
                	<div class="section_name"><span>American Adventure Pavilion</span></div>
                    
                    <div class="pagecontent">
                    	<div class="leftcol">
                            <img src="images/attractions/AMADVPAV_1_998.JPG" width="680" border="0" style="margin:0px 10px 10px 10px;"/>
                            <p>The American Adventure Pavilion is an area in Epcot theme park where Guests of all ages can enjoy experiences that celebrate American history and tradition.</p>
                            <p>Celebrate America at the majestic Colonial-style structure with elements inspired by Independence Hall, Boston's Old State House, Monticello and Colonial Williamsburg. Inside the rotunda you'll find numerous paintings as well as famous quotations from well-known Americans such as Walt Disney, Charles A. Lindbergh, Herman Melville, Ayn Rand, Thomas Wolfe and many others. </p>
        
                            <p>Enjoy a truly American adventure with live musical performances, rousing patriotic entertainment, wonderful exhibits and a fantastic theatrical show at the American Adventure  Pavilion.</p>
                            
                            <p>
                            	<ul class="normal">
                                    <li><strong>Attractions</strong>: Enjoy an inspirational theatrical show, The American Adventure, that combines music, film and audio-animatronics.</li>
                                    <li><strong>Dining</strong>: The Liberty Inn Restaurant</A> serves American fare like cheeseburgers and BBQ, and the kiosk just outside the pavilion offers delicious funnel cakes.</li>
                                    <li><strong>Entertainment</strong>: Voices of Liberty</A> is a group of 10 singers dressed in colonial costumes that sing patriotic and folk songs in harmonized a capella. The Spirit of America Fife and Drum Corps</A> is a group of drummers and fife players that perform rousing patriotic songs outdoors in front of the pavilion. And don't miss the Hall of Flags exhibit, a display of the different flags throughout U.S. history. The outdoor America Gardens Theatre</A> hosts a variety of events throughout the year.</li>
                                    <li><strong>Shopping</strong>: Heritage Manor Gifts offers handcrafted goods, Americana items such as replicas of historical documents like the Bill of Rights and the Declaration of Independence, as well as Voices of Liberty CDs.</li>
                            	</ul>
                            </p>
                        </div>
                        <div class="rightcol">
                        	<div class="prices">
                                Information
                            </div>
                            <div class="information">
                                <b>Location:</b><br />
                                Epcot Theme Park<br />
                                American Adventure Pavilion<br /><br />
                                <b>Height Requirement:</b><br />
                                Any Height<br /><br />
                                <b>Category:</b><br />
                                Fun for Everyone<br />
                                Indoor<br />
                                Outdoor<br /><br />
                                
                            </div>
                            <div class="accepted">
                                Pal Mickey<br />
                                Wheelchair Accessible
                            </div>
                        </div>
                    </div>
                </div>

<!-- Dining Page -->       
                <div id="dining">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                    <div class="section_header dininghead"></div>
                	<div class="section_name"><span>Park Restaurants</span></div>
                    
                    <ul class="rounded">
                        <li class="arrow"><a href="#">Character Dining</a></li>
                        <li class="arrow"><a href="#uniquedining">Unique &amp; Themed Dining</a></li>
                        <li class="arrow"><a href="#">Quick Service</a></li>
                        <li class="arrow"><a href="#">Signature Dining</a></li>
                        <li class="arrow"><a href="#">Casual Dining</a></li>
                        <li class="arrow"><a href="#">Fast Casual Dining</a></li>
                    </ul>
                </div>
                
<!-- Unique Dining Page -->       
                <div id="uniquedining">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                    <div class="section_header dininghead"></div>
                	<div class="section_name"><span>Unique &amp; Themed Dining</span></div>
                    
                    <p>
                    </p>
                    <ul class="rounded">
                        <li class="arrow"><a href="#coralreefrestaurant">Coral Reef Restaurant</a></li>
                        <li class="arrow"><a href="#">Le Cellier Steakhouse</a></li>
                        <li class="arrow"><a href="#">Les Chefs de France</a></li>
                        <li class="arrow"><a href="#">Nine Dragons Restaurant</a></li>
                        <li class="arrow"><a href="#">Restaurant Marrakesh</a></li>
                        <li class="arrow"><a href="#">Rose &amp; Crown Pub &amp; Dining Room</a></li>
                        <li class="arrow"><a href="#">San Angel Inn</a></li>
                        <li class="arrow"><a href="#">Teppan Edo</a></li>
                        <li class="arrow"><a href="#">Via Napoli</a></li>
                    </ul>
                </div>
                
<!-- Coral Reef Restaurant Page -->       
                <div id="coralreefrestaurant">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                    <div class="section_header dininghead"></div>
                	<div class="section_name"><span>Coral Reef Restaurant</span></div>
                    
                    <div class="pagecontent">
                        <div class="leftcol">
                            <img src="images/dining/coralreefrestaurant.jpg" width="680" style="margin-left:10px; margin-bottom:10px;"/>
                            <p>
                            Coral Reef Restaurant, located at The Seas with Nemo &amp; Friends Pavilion at Epcot theme park serves scrumptious seafood for lunch and dinner surrounded by stunning underwater views of the Caribbean Coral Reef.
                            </p>
                            <p>
                            Dine on grilled mahi mahi, pan-seared flounder and other seafood favorites, as well as New York strip steak, grilled chicken and vegetable strudel. All the while, look out on the largest inland saltwater environment ever built— containing 85 different species of tropical fish.
                            </p>
                            <p>
                            Between the delicious food and the extraordinary view, the Coral Reef provides a fascinating and memorable dining experience.
                            </p>
                            <p>
                            Guest Policies
                                <ul class="normal">
                                <li>This experience takes place in a non-smoking environment.</li>
                                <li>Menu items and prices subject to change without notice.</li>
                                <li>Specialty celebration cakes are available for an additional charge and should be ordered 48 hours in advance by calling (407) 827-2253.</li>
                                <li>To make reservations, book online or call (407) WDW-DINE or (407) 939-3463 up to 180 days prior to your visit.</li>
                                <li>This location can accommodate most special dietary needs. Advance notice may be required and cancellation fees may apply. Please indicate any special dietary need at time of reservation booking. Learn more about how we can help accommodate special dietary needs.</li>
                                </ul>
                            </p>
                        </div>
                        <div class="rightcol">
                            <div class="prices">
                                $$$ ($36 to $59.99)
                                Price per person*
                            </div>
                            <div class="information">
                                <b>Location:</b> The Seas with Nemo &amp; Friends Pavilion
                                <b>Cuisine:</b> Seafood<br /><br />
                                <b>Lunch</b><br />
                                Experience: Special &amp; Unique Dining<br />
                                Service: A la Carte<br />
                                Price Level: $$ ($15 to $35.99)<br /><br />
                                <b>Dinner</b><br />
                                Experience: Special &amp; Unique Dining<br />
                                Service: A la Carte<br />
                                Price Level: $$$ ($36 to $59.99)
                            </div>
                            <div class="additional">
                                <ul class="rounded">
                                	<li class="arrow"><a href="#coralreefreservation">Make a Reservation</a></li>
                                    <li class="arrow"><a href="#">Menu</a></li>
                                    <li class="arrow"><a href="#">Coupons</a></li>
                                </ul>
                            </div>
                            <div class="accepted">
                                Disney Dining Plan Accepted
                            </div>
                        </div>
                    </div>
                </div>
                
<!-- Coral Reef Reservation Page -->       
                <div id="coralreefreservation">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                   	<div class="section_header gameshead"></div>
                	<div class="section_name"><span>Coral Reef Restaurant Reservations</span></div>
                    
                    <ul class="rounded">
                        <li><input type="text" placeholder="Name"/></li>
                        <li><input type="text" placeholder="Phone Number"/></li>
                        <li><input type="text" placeholder="Email Address"/></li>
                        <li><input type="text" placeholder="Preferred Reservation Time"/></li>
                        <li><input type="text" placeholder="Preferred Reservation Date"/></li>
                    </ul>
                    
                    <a href="#" class="whiteButton">Submit Reservation</a>
                </div>
                
<!-- Games Page -->       
                <div id="games">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                   	<div class="section_header gameshead"></div>
                	<div class="section_name"><span>Games</span></div>
                    
                    <ul class="rounded">
                        <li class="arrow"><a href="#">Rock the Movies</a></li>
                        <li class="arrow"><a href="#">Honey Bust (AD)</a></li>
                        <li class="arrow"><a href="#">Escape from Moletropolis</a></li>
                        <li class="arrow"><a href="#">Woody's Big Escape</a></li>
                        <li class="arrow"><a href="#">Club Penguin</a></li>
                        <li class="arrow"><a href="#">Robot Riot</a></li>
                        <li class="arrow"><a href="#">Stackle</a></li>
                        <li class="arrow"><a href="#">Box of Spells</a></li>
                        <li class="arrow"><a href="#">Spot the Difference</a></li>
                        <li class="arrow"><a href="#">Bunker Busters</a></li>
                    </ul>
                </div>
                
<!-- Fast Pass Page -->       
                <div id="fastpass">
                    <div class="toolbar">
                        <a class="back" href="#">Back</a>
                    </div>
                   	<div class="section_header fastpasshead"></div>
                	<div class="section_name"><span>Fastpass</span></div>
                    
                    <div class="pagecontent">
                    <p align="left">Disney's <span class="blue10">FASTPASS</span> allows guests to make 'reservations' for a popular ride to avoid waiting in long lines. </p>

                      <p>As you approach the attraction that uses the <span class="blue10">FASTPASS</span> system, you will see three lines. One is the <span class="blue10">FASTPASS</span> distribution line (where you get your <span class="blue10">FASTPASS</span> ticket ), the second is the <span class="blue10">FASTPASS</span> entrance (when you're returning to ride after making your <span class="blue10">FASTPASS</span> reservation), and the third is the Standby entrance for guests not using <span class="blue10">FASTPASS</span>. </p>

                      <p>The <span class="blue10">FASTPASS </span>distribution line features a clock showing what times the tickets are being issued for. A clock with the current time is displayed outside the <span class="blue10">FASTPASS</span> attraction entrance. The Standby line will have the current wait time posted. <br>

                          <br>

                        Let's see how this all works. It's 11:00am and you want to go on Kali River Rapids but there's a 60 minutes wait posted outside the Standby line. You take a look at the <span class="blue10">FASTPASS</span> distribution and see that passes are being issued with a return time of 1:00 - 2:00pm. You get your <span class="blue10">FASTPASS</span> and instead of waiting on a one hour line, you have two free hours before coming back, bypassing the standby line and getting on Kali with little or no wait. </p>

                      <p>For the attractions, the assigned time will give you a 1 hour window to return, so you don't have to run back to be there the minute it goes into effect. With the theater attractions, you'll have a <span class="blue10">FASTPASS</span> for a specific performance. </p>

                      <p>One thing to keep in mind, there are restrictions as to how many passes you can have at once. Your&nbsp; <span class="blue10">FASTPASS</span>  will have the time that you can get your next  <span class="blue10">FASTPASS</span> printed on it. (Usually this is when your current <span class="blue10">FASTPASS</span> can be used or after two hours have elapsed.) Don't plan on going from one <span class="blue10">FASTPASS</span> attraction to another gathering up slips. These machines are smart and won't issue another until your current pass allows it. </p>

<p>Every one in your party will be expected to turn in a <span class="blue10">FASTPASS</span> at the attraction. And please don't return before your scheduled time because you will not be allowed to enter. There's nothing like weaving through a crowd of guests who are blocking the <span class="blue10">FASTPASS</span> entrance because they're too early. Another no-no is trying to use a <span class="blue10">FASTPASS</span> that wasn't issued that day. Don't bother, they can't accept it. Jumping off the standby line into the <span class="blue10">FASTPASS</span> line isn't cool. There will be a Cast Member waiting for you to turn in your non-existent pass who will send you right back to where the Standby line begins. </p>

                      <p><span class="blue10">FASTPASS</span> is available to everyone and works with all admission media. There's no charge for using it. </p>
					</div>
                </div>
                
<!-- Music Page -->       
                <div id="music">
                    <div class="toolbar">
                        <a class="back" href="#about">Back</a>
                    </div>
                    <div class="section_header musichead"></div>
                	<div class="section_name"><span>Disney Music</span></div>
                    
                    <div class="pagecontent">
                    	<div id="jquery_jplayer_1" class="jp-jplayer"></div>
                        <div id="jp_container_1" class="jp-audio">
                            <div class="jp-type-playlist">
                                <div class="jp-gui jp-interface">
                                    <ul class="jp-controls">
                                        <li><a href="javascript:;" class="jp-previous" tabindex="1">previous</a></li>
                                        <li><a href="javascript:;" class="jp-play" tabindex="1">play</a></li>
                                        <li><a href="javascript:;" class="jp-pause" tabindex="1">pause</a></li>
                                        <li><a href="javascript:;" class="jp-next" tabindex="1">next</a></li>
                                        <li><a href="javascript:;" class="jp-stop" tabindex="1">stop</a></li>
                                        <li><a href="javascript:;" class="jp-mute" tabindex="1" title="mute">mute</a></li>
                                        <li><a href="javascript:;" class="jp-unmute" tabindex="1" title="unmute">unmute</a></li>
                                        <li><a href="javascript:;" class="jp-volume-max" tabindex="1" title="max volume">max volume</a></li>
                                    </ul>
                
                                    <div class="jp-progress">
                                        <div class="jp-seek-bar">
                                            <div class="jp-play-bar"></div>
                                        </div>
                                    </div>
                                    <div class="jp-volume-bar">
                                        <div class="jp-volume-bar-value"></div>
                                    </div>
                                    <div class="jp-current-time"></div>
                                    <div class="jp-duration"></div>
                                    
                                </div>
                
                                <div class="jp-playlist">
                                    <ul>
                                        <li class="radiolist"></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
<!-- Video Page -->       
                <div id="movies">
                    <div class="toolbar">
                        <a class="back" href="#about">Back</a>
                    </div>
                    <div class="section_header musichead"></div>
                	<div class="section_name"><span>Watch Disney Videos</span></div>
                    
                    <div class="pagecontent">
                    
                    <div id="jp_container_2" class="jp-video jp-video-270p">
                        <div class="jp-type-playlist">
                            <div id="jquery_jplayer_2" class="jp-jplayer"></div>
                            <div class="jp-gui">        
                                <div class="jp-video-play">        
                                    <a href="javascript:;" class="jp-video-play-icon" tabindex="1">play</a>
                                </div>
                                <div class="jp-interface">
                                    <div class="jp-progress">
                                        <div class="jp-seek-bar">
                                            <div class="jp-play-bar"></div>
                                        </div>
                                    </div>
                                    <div class="jp-current-time"></div>
                                    <div class="jp-duration"></div>
                                    <div class="jp-title">
                                        <ul>
                                            <li></li>
                                        </ul>
                                    </div>
                                    <div class="jp-controls-holder">
                                        <ul class="jp-controls">
                                            <li><a href="javascript:;" class="jp-previous" tabindex="1">previous</a></li>
                                            <li><a href="javascript:;" class="jp-play" tabindex="1">play</a></li>
                                            <li><a href="javascript:;" class="jp-pause" tabindex="1">pause</a></li>
                                            <li><a href="javascript:;" class="jp-next" tabindex="1">next</a></li>
                                            <li><a href="javascript:;" class="jp-stop" tabindex="1">stop</a></li>
                                            <li><a href="javascript:;" class="jp-mute" tabindex="1" title="mute">mute</a></li>
                                            <li><a href="javascript:;" class="jp-unmute" tabindex="1" title="unmute">unmute</a></li>
                                            <li><a href="javascript:;" class="jp-volume-max" tabindex="1" title="max volume">max volume</a></li>
                                        </ul>
                                        <div class="jp-volume-bar">
                                            <div class="jp-volume-bar-value"></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="jp-playlist">
                                <ul>
                                    <!-- The method Playlist.displayPlaylist() uses this unordered list -->
                                    <li></li>        
                                </ul>        
                            </div>
                        </div>
                    </div>
                    </div>
                </div>
            

            

        
            
<!-- ----------------------------------------------------------------- Close Content Area ----------------------------------------------------- -->
        </div>
        <div id="loader">
            <div id="overlay"><img src="images/ajax-loader.gif" width="32" height="32" border="0"/><br /><br />Loading...</div>
        </div>
    </body>
</html>