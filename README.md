# CSS3 Marquee
Jquery plugin for marquee effect using CSS3. [Demo](http://cdn.rawgit.com/nviswanathan/Css3Marquee/master/index.html)



# Why?

The default marquee html tag animation is not smooth in all browsers. It's looks very choppy in all browsers except Chromium and Chrome. So we decided to use CSS3 animation property to solve this problem. It will work in WebKit as well. 



## Dependncy	

1. [Jquery](http://code.jquery.com/jquery-1.9.1.js)



## Usage

1. Include below script tag in to your html page
   ```html
   <script type="application/javascript" src="//cdn.rawgit.com/nviswanathan/Css3Marquee/master/marquee.js"></script>
   ```

2. Create Your Marquee content
   ```html
   <div>
   	<p class="righttoleft" data-direction='left'>Css 3 Based Marquee</p>
   </div>
   ```

3. Select your content and apply the effect
   ```javascript
   $('.righttoleft').Css3Marquee();
   ```

## Options

You can change the options in two ways:

1. Use HTML data attribute.

   ```html
   <p class="righttoleft" data-direction='left' data-speed=10>Css 3 Based Marquee</p>
   ```

2. Params.

   ```javascript
   $('.righttoleft').Css3Marquee({
   	direction:'left',
   	speed: 10
   });
   ```


### Default 

```javascript
{
  direction:'left', //['left', 'right', 'bottom', 'top']
  speed:10
}
```



# TODO:

1. ​
