---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

callforaction:
  url: https://preview.memlock.io
  text: Memlock Web
  style: alert

header:
widget1:
  title: "Memlock Web"
  url: https://preview.memlock.io
  image: widget-1-302x182.jpg
  text: ''
widget3:
  title: "Support"
  url: 'https://memlock.atlassian.net/servicedesk/customer/portal/1'
  image: widget-github-303x182.jpg
  text: ''
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
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
