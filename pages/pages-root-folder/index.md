---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: firstbannerattempt2.jpg
widget1:
  title: "About Sam Harrison"
  url: '/getting-started/'
  image: widgetaboutsam.jpg
  text: 'Every nutter has a story. Join Sam for a biscuit, tune in and drop out for a deep discussion and journey through the expanded collective consciousness, from the ice-age to the dole-age. Actually, second thoughts, just visit our about page.'
widget2:
  title: "Watch & Listen"
  url: '/pages/videos/'
  image: widgetmedia.jpg
  text: 'Sam is making new music every single week, see the best of our <a href="/pages/music/">Music</a> & <a href="/pages/videos/">Videos</a> by clicking here... Check out our <a href="https://www.facebook.com/samofthex/">Facebook Feed</a> for the absolute latest!'
  
widget3:
  title: "Get Involved"
  url: 'http://eepurl.com/bLaXTL'
  image: widgetgetinvolved.jpg
  text: '<em>Wanna be part of something?</em> Get in touch from our <a href="http://samharrisonmusic.com/contact/">Contact Page!</a> Join our <a href="http://samharrisonmusic.us12.list-manage1.com/subscribe?u=bdb758a69c11780dc26ae7581&id=0f979f44e4">Mailing List!</a> Check out our <a href="https://www.facebook.com/samofthex/">Facebook</a>, our <a href="https://twitter.com/samofthex">Twitter</a>, our <a href="https://www.youtube.com/user/samofthex">Youtube</a>, & our <a href="https://soundcloud.com/samharrisonmusic">Soundcloud</a>... Thankyou for the support, with lots of love! xxx'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: http://eepurl.com/bLaXTL
  text: Join our mailing list xxx ›
  style: alert
permalink: /index.html
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://youtu.be/6PBrOIzBkG8" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>


#<a href="#" data-reveal-id="videoModal">