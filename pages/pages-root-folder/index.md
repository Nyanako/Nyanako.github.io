---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-home.jpg
widget1:
  title: "Blog"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: "Here you'll be able to catch up with my latest development ramblings or projects. I don't update much, but when I do feel free to check it out and let me know what cha think~"
widget2:
  title: "Who Am I?"
  url: '/design/portfolio/'
  text: "I'm graduate student of CGI who's skills lie in 3D model design and creation, texturing, surfacing, material generation and environment creation. I've worked in small teams and always strive and seek to learn new workflows and skills."
#  text: "<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href='http://foundation.zurb.com/'>Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,..."
  video: "<a href='#' data-reveal-id='videoModal'><img src='https://i.ytimg.com/vi/-c5YHMYiKYw/hqdefault.jpg?sqp=-oaymwEZCNACELwBSFXyq4qpAwsIARUAAIhCGAFwAQ==&rs=AOn4CLB13BW9nB2nXxflDvnLtibsIdWqAg' width='302' height='182' alt=''/></a>"
widget3:
  title: "Artstation"
  url: 'https://www.artstation.com/nyanako'
  image: widget3-artstation-302x182.jpg
  text: "Just to let ya know, my work is also hosted onto <a href='https://www.artstation.com/nyanako'>Artstation</a> which I highly recommend you to checkout! <br/><br/>As well as this my other reachable social links are linked below in the footer. Thanks for checking out the site. ~.^"
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/-c5YHMYiKYw" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>