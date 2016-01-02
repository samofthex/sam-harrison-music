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
  text: 'Every nutter has a story. Join Sam for a cider, tune in and drop out for a deep discussion and journey through the expanded collective consciousness, from the ice-age to the dole-age. Actually, second thoughts, just visit our about page.'
widget2:
  title: "Watch & Listen"
  url: '/getting-started/'
  text: '<em>Sam Harrison</em> is is an artist you should be listening to. Why?'
  video: '<img src="http://samofthex.github.io/sam-harrison-music/images/widgetmedia.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Get Involved"
  url: 'http://eepurl.com/bLaXTL'
  image: widgetgetinvolved.jpg
  text: '<em>Wanna be part of something?</em> Then tell me via Twitter <a href="http://twitter.com/samofthex">@samofthex</a>.'
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
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://youtu.be/6PBrOIzBkG8" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>


#<a href="#" data-reveal-id="videoModal">