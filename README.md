# YouTube PopUp jQuery Plugin
jQuery plugin to display YouTube video or Vimeo video in PopUp, responsive &amp; retina, Compatible with WordPress, Autoplay support, easy to use.

##Usage

Easy to use, include jQuery and YouTubePopUp plugin and Style:

    <link rel="stylesheet" type="text/css" href="YouTubePopUp.css">
    <script type="text/javascript" src="jquery-1.12.1.min.js"></script>
    <script type="text/javascript" src="YouTubePopUp.jquery.js"></script>
    <script type="text/javascript">
      jQuery(function(){
          jQuery("a.bla-1").YouTubePopUp();
          jQuery("a.bla-2").YouTubePopUp( { autoplay: 0 } ); // Disable autoplay
      });
    </script>
  
Now add class to links, for example:

    YouTube:
    <a class="bla-1" href="https://www.youtube.com/watch?v=3qyhgV0Zew0">With Autoplay</a>
    <a class="bla-2" href="https://www.youtube.com/watch?v=3qyhgV0Zew0">Without Autoplay</a>
 
    Vimeo:
    <a class="bla-1" href="https://vimeo.com/81527238">With Autoplay</a>
    <a class="bla-2" href="https://vimeo.com/81527238">Without Autoplay</a>

For WordPress use Video PopUp plugin: https://wp-time.com/video-popup-plugin-for-wordpress/#live-demos

Enjoy,
WPTime.
https://wp-time.com
