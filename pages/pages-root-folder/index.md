---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage_new 

header:
  headline: An institute to support academic & community collaborations in the digital humanities
  byline: Hosted by the Institute for Digital Research in the Humanities<br>University of Kansas, Lawrence, KS <br>June 6-11, 2022
breadcrumb: false  
 

widget1:
  title: "About"
  url: '/about/'
  # image: widget-1-302x182.jpg
  text: 'Hosted by the Institute for Digital Research in the Humanities at the University of Kansas, PDHI is intended to foster successful academic-community digital, public-facing humanities projects.'
widget2:
  title: "Curriculum"
  url: '/curriculum/'
  # image: widget-github-303x182.jpg
  text: 'The curriculum includes an intense week of case studies, technical training, and workshops & discussions intended to strengthen relationships, create sustainable projects, and provide foundational knowledge of tools and methods in the public digital humanities.'
widget3:
  title: "Faculty"
  url: '/faculty/'
  # image: widget-1-302x182.jpg
  text: 'The Institute sessions will be led by more than 20 experienced academics and community partners, offering a breadth of complementary skill sets and areas of expertise that will provide participants rich opportunities for engagement.'



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
 # url: https://{{site.url}}}/apply/
 # text: Apply
 # style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<!--
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
-->