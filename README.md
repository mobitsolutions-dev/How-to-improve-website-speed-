# How to improve website speed ?
    
1) Download the lazysizes Javascript library . Once download ,include it in your page through following script tag :

     <script src="lazysizes.min.js" async=""></script>

2) within your HTML 
```
<img> tag:
```
* Add class="lazyload" attribute to all images
* Change the src attribute to data-src
 
    <!--Use data-src. And,specify lazyload class-->
```
    <img data-src="image.jpg" class="lazyload"/>
```
