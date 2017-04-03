---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: maxteaching.jpg
widget1:
  title: "Blog"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: 'For a quick glimpse at the stuff running around inside my head <em>check out my blog/em>'
widget2:
  title: "Make a difference"
  url: '/shareSTEM/'
  text: '<em>STEM</em> is more than a passion, its how I understand the world. Through my robotics team, I get to share this approach with many kids.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/reignonmxp.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Projects"
  url: '/random/'
  image: widget-github-303x182.jpg
  text: '<em>Long term Projects</em> This is where I say something about larger projects.'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
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
    <iframe width="1280" height="720" src="https://youtu.be/0n70dlEw9P4" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
