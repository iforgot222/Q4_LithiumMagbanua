# Seatwork #2 - Getting to know CSS Position and z-index.
### This seatwork will ask you to implement the different CSS position on a given code.
### short link to this .md file is: https://bit.ly/4c61P9K
#### Resources (also found in Khub week 5)
- [4 Minute Youtube Video on CSS Position](https://www.youtube.com/watch?v=YEmdHbQBCSQ)
- [CSS Position Tutorial](https://roycan.github.io/CssPositioningZIndexLab/)

### Instructions: 
1. This is individual submission in khub, but you can work with a partner.  When you submit in khub please place both your names in the submission bin.
2. Guided Activity (30 minutes), please follow what is being required.  

    - Make a copy of this .md file to your Q4 repository and name it as **SectionLNseatwork2.md** example **9LiCruzSeatwork2.md**. Place it in your q4 repository vscode local computer. Committing frequently to your Github repository.  
    - Copy the code below and paste it inside a new file (name it as SectionLNseatwork2.html). Place this file in the same location where the .md file is saved. 
    - Change the content values of the meta tags to your names for author/s and the date today for revised.
    - Please do the following tasks that will ask you to reposition HTML elements then answer the guided question for each task on the .md file. Commit changes to the .md file and to the .html file as well.
    **- This seatwork is worth 20pts and should be submitted by the end of the period** The link to [KHub submission bin](https://khub.mc.pshs.edu.ph/mod/assign/view.php?id=15481).
      - Submit the links to your .md file and .html file.


### Step 1 (Static vs Relative):

- Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.

It moves the sidebar rectangle regardless of the position of the other rectangles in the page, and it allowed be to set a specific position for the sidebar without affecting other rectangles. However, when all is set to zero, it well position itself normally based on the content of the page.

### Step 2 (Fixed):

- Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?

When I scroll down the page, the footer remains at the bottom and fixed there despite zooming in or zooming out. If differs from relative because the footer will always stay fixed onto the bottom of the page, regardless of the content.

### Step 3 (Absolute):

- Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?

Fixed stays on the screen despite scrolling and zooming in while Absolute doesn't. Additionally, setting all directions to zero for absolute, is positions itself regardless of the surrounding content and ends up on the very top or bottom (when top or bottom is zero).


### Step 4 : (Absolute)

- Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?

If you switch the z-index values, the main content will be positioned on top of the notice box when notice is at z index 2 and content at z index 1. The z index indicates the positioning of layers, with the higher (2) being at the back and lower number in front (1).

- Challenge: 
    * What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
    * Try to change the position of .content to relative then to fixed. What do you observed each time?
    * What do you observe on about the effect of z-index on .notice and .content boxes?

3. Please answer the following reflection questions (15 minutes)

    a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)? 
      Static: the contents of the page follow normal or defualt positioning
      Relative: the contents will still follow the normal positioning but can be positioned based on that
      Absolute: the contents will not follow the normal positioning or flow and is positioned to its nearest positioned ancestor 
      Fixed: placed regardless of normal flow and to the viewport, will remain on the page even after zoomed in or scrolled

    b. How does absolute positioning depend on its parent element?
      - its position will be relative to the first parent element, will disregard normal flow 
      - if there is no acestor, its position will be based on the viewport or the page itself, also still regardless of normal flow

    c. How do you differentiate sticky from fixed (you can research on sticky)?
      Fixed: Stays there regardless of scrolling or zooming in the page, will always stay on screen
      Sticky: It moves when you scroll, but after reaching a certain point, it sticks there only while its on screen and will go away when you scroll

    d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.
      1) The fixed position can be used when you want a certain note of information to be seen and remembered all throughout the page as they scoll
      2) Z index to emphasize the levels of importance of each section
      
      

