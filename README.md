# Defer Offscreen Images | How to improve website speed ?

## First create simple Gallery images wesite in HTML and check Google speed testing 

https://developers.google.com/speed/pagespeed/insights/


<b> 1) Download the lazysizes Javascript library . Once download ,include it in your page through following script tag :</b>
```
     <script src="lazysizes.min.js" async=""></script>
```
<b> 2) within your HTML ```<img> tag:``` </b>

* Add class="lazyload" attribute to all images
* Change the src attribute to data-src
 
    <!--Use data-src. And,specify lazyload class-->
```
    <img data-src="image.jpg" class="lazyload"/>
```
<b> After Defer Offscreen Images </b>
<img src="images/After.png" height="100" width="100">
<b>Before Defer Offscreen Images</b>
<img src="images/Before.png" height="100" width="100">
