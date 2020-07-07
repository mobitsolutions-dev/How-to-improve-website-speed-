# How to improve website speed ?
    
<b> 1) Download the lazysizes Javascript library . Once download ,include it in your page through following script tag :</b>
```
     <script src="lazysizes.min.js" async=""></script>
```
###### 2) within your HTML ```<img> tag:```

* Add class="lazyload" attribute to all images
* Change the src attribute to data-src
 
    <!--Use data-src. And,specify lazyload class-->
```
    <img data-src="image.jpg" class="lazyload"/>
```
![Before](https://user-images.githubusercontent.com/67701415/86772382-58159880-c06d-11ea-87d2-a10f5567ba2c.png)
![After](https://user-images.githubusercontent.com/67701415/86772390-5b108900-c06d-11ea-8182-bead6102c675.png)
