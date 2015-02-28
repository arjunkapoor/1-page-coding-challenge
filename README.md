# 1-page-coding-challenge

I have a couple of things I would like to mention.

1. I used CSS media queries instead of bootstrap as bootstrap was making it a little messy since the bacground image 
has a fixed size and would not fill the entire height of the page if I stack the iPhone frame below the left side 
content (which happens when using bootstrap). I tried a couple of different techniques such as using height: 100% or 
using center, cover & fixed for background but it seemed to not work after a certain point when I pulled down the 
iPhone frame after certain breakpoints. 

2. With CSS media queries I decided to have three breakpoints. I understand that having three breakpoints means three 
different requests to load a different CSS (might be a bad practice for page load/optimization techniques). 
But the reason for that is that if I went with less breakpoints, I would have had to scale all the images in photoshop 
according to the page and that would take a little more time.

3. First breakpoint occurs at 1130px, second occurs at 1015px, third occurs at occurs at 700px. For the last breakpoint 
I scaled the iPhone image using photoshop so that at least for the purpose of it, the page should look good on devices 
with width from 600px to 700px. Below 600px I would have had to scale other images as well as mentioned earlier. 
