---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default #can be home for blog, currently changed to be page
title: Home

#adding an image
#first ![image description](/name of the actual file)
#with this, you can't change the image size - need to html...do like lab website?
#

#come back to this when I can figure out why the links are weird!
#<div style="width: 400px; height: 560px; overflow: hidden; position: relative;">
 # <img src="https://i.ibb.co/NdDTHJ1q/image.jpg" 
    #   onmouseout="this.src='https://i.ibb.co/NdDTHJ1q/image.jpg'" 
     #  onmouseover="this.src='https://i.ibb.co/ccLMxTsJ/image.jpg'" 
     #  alt="liz picture" 
      # style="width: 100%; height: 100%; object-fit: cover;">
#</div>

#<div align="left" style="max-width: 1200px; margin: 0 auto; text-align: left;" markdown="1"> 

#this centers whatever is inside (margin: 0 auto) and aligns it left within block
#the block can take up a max of 1200px, no margin btw top/bottom of page and block
#markdown = 1 is just necessary i think ... i was less clear on this one idk

#and then <div> after all text

---
<div style="max-width: 1200px; margin: 0 auto; text-align: left;" markdown="1">

## Welcome to my website!

<div style="width: 400px; height: 560px; overflow: hidden; position: relative;">

  <img src="https://i.ibb.co/Zhdk7VM/liznow.jpg" 
       onmouseout="this.src='https://i.ibb.co/Zhdk7VM/liznow.jpg'" 
       onmouseover="this.src='https://i.ibb.co/LyQrQQ8/Liz-B-Baby.jpg'" 
       alt="liz picture" 
       style="object-fit: cover; width: auto; height: auto;">
</div>      

Click to learn more about [my interests](/about/), [my current research projects](/research/), and access my [CV](/files/BrachtCV_8.14.2026.pdf).

</div>
