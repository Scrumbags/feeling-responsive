---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "scrumbags-website-banner.png"
widget1:
  title: "YouTube"
  url: 'https://www.youtube.com/channel/UCX8IDeRO8D0urJUckUSqObw'
  image: scrumbags-website-widget-youtube.png
#  text: ''
widget2:
  title: "Spotify"
  url: 'https://open.spotify.com/show/557Kg8sGYRthZdgfmXpVQg?si=qN3n5FYxSpGoYyVD6zLXtg'
  image: scrumbags-website-widget-spotify.png
#  text: ''
widget3:
  title: "iTunes"
  url: 'https://podcasts.apple.com/de/podcast/scrumbags/id1556203015'
  image: scrumbags-website-widget-itunes.png
#  text: ''
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
  url: /fragen/
  text: Sende uns deine Fragen ›
#  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!--<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>-->
