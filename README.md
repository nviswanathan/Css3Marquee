# Css3 Marquee
Jquery plugin for marquee effect using css3



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

3. Select your content and apply this effect
   ```javascript
   $('.righttoleft').Css3Marquee();
   ```

## Options

You can changes the options in two way.

1. Use HTML data attriute.

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

