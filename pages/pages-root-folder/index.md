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
  title: "Blog and Projects"
  url: '/blog'
  image: widget-1-302x182.jpg
  text: '<em>Take a look at my blog</em> to get a feel for my recent endeavors - Updates about my work in robotics, my progress on independent projects, my performance at competitions, and more go here.'
widget2:
  title: "Making a difference"
  url: '/blog/community'
  text: '<em>STEM is more than just a passion,</em> it is how we understand everything from the quantum level to the cosmic. With my robotics team, I get to share this approach with the world.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/reignonmxp.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Academics"
  url: '/academics/'
  image: college302x182.jpg
  text: '<em>College Bound!</em> With the end of my time at the Science and Engineering (Magnet) at Dallas on the horizon, now comes the time to ensure that my aspirations to help others by pushing the boundaries of prosthetics does not go to waste.'
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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe src="https://www.youtube.com/embed/0n70dlEw9P4?ecver=2" width="1280" height="720" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
