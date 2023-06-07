---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: aetna_sunset.jpg
widget1:
  title: "Publications"
  url: '/publications/'
  image: pub-widget-302x182-ratio.png
  text: 'Complete bibliography with PDFs'
widget2:
  title: "Research"
  url: '/research/'
  image: afec.png
  text: 'Research topics and projects'
widget3:
  title: "Members"
  url: '/members/'
  image: widget3.jpg
  text: 'Affiliated Researchers & Dr. Cooper'
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
  url: https://www.unk.edu/academics/biology/index.php
  text: More information about where I work ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
