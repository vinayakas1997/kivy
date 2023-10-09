# this file is to get know about building the mobile applications from kivy 
1. Understanding the layout 
 1.1 Box layout 
 1.2 Anchor layout 
 1.3 Grid layout 
 1.4 Stack layout 
 1.5 Scroll view 
 1.6 Page layout 
 ----------------
 1.7 Float layput 
 1.8 Relative layout 
 1.9 scatter layout


 ##Box layout  
 default the orientation is horizontal then we can change into vertical 
 then we can adjust the position of the button using x,center_x,right (for horizontal)
 and for vertical y,center_y,top(for vertical)

##Anchor layout
Here main things to focus to chnage the position of the button is 
anchor_x-->right,left,center
anchor_y-->top,bottom,center


##Grid Layout 
Here main things to focus on is rows amd cols.
rows:3
cols:2 so it creates two 3 rows and 2 columns 

##Stack Layout
The main things is kept in t he mind are how the stacking takes place 
 ===left-right top-bottom(default --> lr-bt)
orientation:"rl-bt"(right to left and bottom to top)
padding:("20dp","20dp","20dp","20dp")--> it takes four values gives the space between the box and the borders 
spacing:("20dp","20dp") --> This gives the spacing between the boxes horizontal and vertical

##Scroll view 
Think that I have 100 buttons so as it is more than the size of the default window so we can use the scroll view 
The main thing we have to keep in the mind is the isto define the size of the width and height 
if you want to scroll only down wards then use the height and give your own value 
If you want sufficienyt height then we can definew by 
height:self.minimum_height 
