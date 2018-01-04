---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "scrumbags-logo-green.png"
widget1:
  title: "Manifest"
  url: '/manifesto/'
  image: manifest-thumb.png
  text: 'Das Wissen und das Kollektiv von Erfahrungen, die sich hinter <em>agile</em> verbegen, wollen wir mit der Welt teilen. Erfahre im scrumbags Manifest welche Werte für uns dafür Zentral sind.'
widget2:
  title: "Blog"
  url: '/blog/'
  image: blog-thumb.png
  text: 'In unserem Blog teilen wir Wissen und Erfahrungen zu Themen rund um agile, Lean und Beta-Codex. Klick dich mal durch und mit etwas Glück findest du ein Thema, das etwas in dir bewegt.'
widget3:
  title: "Autoren"
  url: '/authors/'
  image: autoren-thumb.png
  text: 'Finde heraus wer wir sind! scrumba.gs wird mit Inhalten von mehreren Autoren gefüttert. Willst du auch ein scrumbag sein? Lass es uns <a href="http://www.google.com">hier</a> wissen.'
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
  text: Informier mich wenn die scrumbags was neues haben ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
