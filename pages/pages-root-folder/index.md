---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "scrumbags-logo-website.png"
#widget1:
#  title: "Manifest"
#  url: '/manifesto/'
#  image: manifest-thumb.png
#  text: 'Wir wollen Wissen und Erfahrungen rund um Agile, Lean, Beta-Codex usw. mit euch teilen. Erfahre in unserem Manifest, wofür wir das hier machen und was dabei für uns zentral ist.'
#widget2:
#  title: "Blog"
#  url: '/blog/'
#  image: blog-thumb.png
#  text: 'Der Blog ist das Herz der Scrumbags. Klicke dich doch mal durch und schaue, was vielleicht nützlich für dich ist oder etwas in dir bewegt.'
#widget3:
#  title: "Autoren"
#  url: '/authors/'
#  image: autoren-thumb.png
#  text: 'Finde heraus, wer wir sind! Die Scrumbags-Plattform wird mit Inhalten mehrerer Autoren gefüttert. Willst du auch ein Scrumbag sein? <a href="/contact/">Lass es uns wissen</a>!'
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
## callforaction:
##  url: https://tinyletter.com/feeling-responsive
##  text: Informiere mich über Updates ›
##  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
