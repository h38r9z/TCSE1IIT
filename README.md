java cTCSE1IIT Lab   6 – HTML and PHP 
In this lab we will continue our work from last week.
Please make sure you have completed Lab 05 from last week before starting this lab.
Open up your IITWebLab web page from last week.
We will first try to make our page look nicer using CSS.
If you have any strange issues with the CSS/HTML make sure you run it though the validator to check for any errors. http://html5.validator.nu and paste in the URL of your page (or you can select Text Field and past in your HTML)
Task 0 
As we are continuing our work from previous week’s lab, make sure XAMPP is properly started and navigate to the IITWebLab folder inside C:\xampp\htdocs.
Create a new folder named fruitpics. Download fruitPics.zip from Moodle and copy the three pictures to the newly created folder. These pictures are different to the lab 5 ones because they are smaller.
Task 1 
Centre the main div and the header div. The simplest way to do this is to define a max-width of about 80em and setting margin-left and margin-right to auto.
Instead of making two separate CSS definitions you can make just one and have both the divs share it by providing both the IDs separated by a comma like so.
#main, #header 
Please note that you should full screen (maximise) the browser win代 写TCSE1IIT Lab 6 – HTML and PHPR
代做程序编程语言dow to see the effect. Finally remove the text-align CSS from the header div, so that it returns to the left side.
Task 2
Remove the background color from the header div. Set the text color for the header div to #E60418 Set the navbar background color to   #BC5510
Remove the background color from the  tags in the navbar. 
NOTE: when I say to remove a property, you should delete the line of code that causes it. In this case you should delete the background-color property. 
Task 3  
Try setting the navbar div to be centred using the same CSS as Task 1 and see what happens. 
You can reduce duplicate code by simply adding #navbar to the CSS definition from Task 1 like so: 
#main, #header, #navbar  
Task 3A  
Unfortunately, this does not do what we want. 
What we can do instead is centre the UL tag inside the navbar rather than the navbar div itself. 
#main, #header, #navbar ul  
Task 4  
Set the text-decoration to none for the  tags in the navbar and set the text colour to white. text decoration refers to the underline that hyperlinks have. 
Change the hover background colour to #A50613 
To get the left and right edges of the navbar to touch the edge of the screen set the margin to 0px on the body tag. 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
