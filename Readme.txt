You can see the Dogecoin Timeline at DogecoinTimeline.com . 
Actions and events in Dogecoin Timeline are real. You can visit, lurk, or get involved in the Dogecoin community 
by going to Discuss.Dogecoin.com, Reddit.com/r/Dogecoin, or on Facebook, Twitter, or even Twitch. Shibes are multiplying and are moonbound. 





Support the Dogecoin Timeline @ DMhq1vJMkCbd3PH8sqRxT6vgy62cJMDu9R 




**Dogecoin Timeline INFO** 
You DO NOT need to download files to place the timeline on your website. 
All you need to do, is paste an <iframe> into the HTML of your site. If there are Any issues, contact me on Reddit /u/4moves. 


Dogecoin timeline is a Google Spreadsheet file containing list of all the dogecoin events. 


**FILE INFO**
The "DogecoinEventLog" spreadsheet is The Dogecoin Timeline. 
The "DogecoinHighlights" spreadsheet is 4move's take on what Issues are important to Dogecoin. 








--Add TIMELINE TO WEBSITE-------------------------------------------------------------
------------------------------------------------------------------------------------
------------------------------------------------------------------------------------

To put timeline on your website Follow the steps for each timeline. 

There is three different quick start Timeline to choose from. 



--TIMELINE VERSIONS--
Version 1: Day1 to Last day -- The Timelines will start from Day 1 of Dogecoin to the Last Day of Dogecoin. 
Version 2: Last Day to Day1 -- The Timelines will start from the Last day of Dogecoin to the First Dogecoin.
Version 3: Starting Slide   -- The Timelines will start from a certain Slide, managed by DogecoinTimeline.com




--------------------------------VERSION 1------------------------------------


**Start From Day1 to Last Day**



	1) Event Log [Start - 10/20/14]


		--Copy <iframe> to html page. 
		----------------------------


		<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0At3GjVZJ_LVrdHNhTlVnRXRPcnBUYXdMZURweXJhUnc&font=Bevan-PotanoSans&maptype=toner&lang=en' width='100%' height='100%' frameborder='0'></iframe>
		

		---------------------------
		--Go have a glass of water and relax, You're Done! 





	2) Highlights (according to 4moves) [Start - 10/20/14]


		Step 1: Copy this to your Html page. 
		----------------------------




		<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0At3GjVZJ_LVrdFktT0VURUhpWFJyZmhhM2ZKVUQzVHc&font=Bevan-PotanoSans&maptype=toner&lang=en' width='100%' height='100%' frameborder='0'></iframe>




		----------------------------
		Step 2: Go have a glass of water and relax, You're Done!


--------------------------------VERSION 1------------------------------------











--------------------------------VERSION 2------------------------------------

**Last Day to First Day**


	1) Event Log [Start - 10/20/14] ---Copy iframe to HTML---


<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0At3GjVZJ_LVrdFktT0VURUhpWFJyZmhhM2ZKVUQzVHc&font=Bevan-PotanoSans&maptype=toner&lang=en&start_at_end=true&hash_bookmark=true' width='100%' height='100%' frameborder='0'></iframe>


						--- 		---

	
	2) Highlights (according to 4moves) [Start - 10/20/14] ---Copy iframe to HTML---


<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0At3GjVZJ_LVrdHNhTlVnRXRPcnBUYXdMZURweXJhUnc&font=Bevan-PotanoSans&maptype=toner&lang=en&start_at_end=true&hash_bookmark=true' width='100%' height='100%' frameborder='0'></iframe>






--------------------------------VERSION 2------------------------------------










--------------------------------VERSION 3------------------------------------


**SET A STARTING SLIDE**

--This Timeline requires a little bit more work on the part of the Developer. 
--The starting Slide is maintained by the DogecoinTimeline website. 
--To add this version to your website.
	Step 1: Copy and Paste PHP into your HTML Site. 
	Step 2: Copy a timeline's Iframe and Paste it into your HTML site. 
	Step 3: Relax, you are done. Get yourself a cookie, and take your seat on the rocket. 






---COPY The PHP below and above the DO NOT COPY lines------------------------
---DO NOT COPY THIS LINE-----------------------------------------------------





<?php 
//Grab xml file
$xmlfile = file_get_contents("http://DogecoinTimeline.com/DTimages/Slide.xml");
//Convert to string. 
$ob = simplexml_load_string($xmlfile);
//Convert String to JSON Array
$json = json_encode($ob);
//Convert JSON Array back to PHP Array
$array = json_decode($json, true);

/* ------ The variable $array holds the starting slides for each timeline. 
		  You can accessed the values by using PHP and 
		  
		  				echo $array["HighLights"];
							
								or 
								
						echo $array["EventLog"];
						

*/
?>



---DO NOT COPY THIS LINE---------------------------------------------------



---COPY the Timelines you want.




	1) Event Log [Start - 10/20/14] ---Copy iframe to HTML---


<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0At3GjVZJ_LVrdFktT0VURUhpWFJyZmhhM2ZKVUQzVHc&font=Bevan-PotanoSans&maptype=toner&lang=en&start_at_end=true&hash_bookmark=true&start_at_slide=<?php echo $array["HighLights"]; ?>' width='100%' height='100%' frameborder='0'></iframe>


						--- 		---

	
	2) Highlights (according to 4moves) [Start - 10/20/14] ---Copy iframe to HTML---


<iframe src='http://cdn.knightlab.com/libs/timeline/latest/embed/index.html?source=0At3GjVZJ_LVrdHNhTlVnRXRPcnBUYXdMZURweXJhUnc&font=Bevan-PotanoSans&maptype=toner&lang=en&start_at_end=true&hash_bookmark=true&start_at_slide=<?php echo $array["EventLog"]; ?>' width='100%' height='100%' frameborder='0'></iframe>













--------------------------------VERSION 3------------------------------------















------------------------------------------------------------------------------------
------------------------------------------------------------------------------------
--END QUICK START-------------------------------------------------------------------














--





























--
-
---
-
--
--
-
---
-
--
--
-
---
-
--
--
-
---
-
--
--
-
---
-
--
--
-
---
-
--
--
-
---
-
--
--How to Create Your own Highlights ------------------------------------
------------------------------------------------------------------------
------------------------------------------------------------------------


Step by Step
1) Download this package.
2) Go to google drive, and Import 'DOGECOIN_EVENT_LOG' spreedsheet. 
3) Next, Download the 'Template Spreedsheet' from this link and open it in Google Drive. -- https://drive.google.com/previewtemplate?id=0AppSVxABhnltdEhzQjQ4MlpOaldjTmZLclQxQWFTOUE&mode=public
4) Now, Compare the spreadsheet, and ensure you have imported the 'Dogecoin_Event_LOG' correctly by looking at the Headers in each spreedsheet, are the same. 
5) Delete everything except row 1. 
6) Each ROW is an event. 
  -To add events, You can follow the Headers and The examples in the 'DOGECOIN_EVENT_LOG'.
  -OR Copy a Row from the 'DOGECOIN_EVENT_LOG'








**MORE INFO**

	>>>>) Using Other Links -- 

	-Open the DogecoinTimeline folder. 
	
	-Open links.txt
	
	-Copy any link you want

	-Now go to http://timeline.knightlab.com 
	
	-Create a new timeline. Enter the url you copied from google drive into the box. 
	
	-Copy the generated Iframe into your html. 
	 
		


	>>>>) Creating and Using Your own URL --

	-Go to google drive, and import a new document. 

	-Navigate to the DogecoinTimeline folder. 

	-Open Timeline folder and Find DT_8-24-14 and import the file. 

	-Make whatever changes you want. 

	-In google drive - Click File -> Publish -> Copy the url in the textbox. 

	-(FYI: You can Submit your changes to the DogecoinTimeline) 
	
	-Now go to http://timeline.knightlab.com 
	
	-Create a new timeline. Enter the url you copied from google drive into the box. 
	
	-Copy the generated Iframe into your html. 
	



	
	

