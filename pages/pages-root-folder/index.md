---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage or frontpage_new
#
#

layout: frontpage_new 

header:
  headline: An institute to support academic & community collaborations in the digital humanities
  byline: Hosted by the Institute for Digital Research in the Humanities<br>University of Kansas, Lawrence, KS <br>June 6-11, 2022
breadcrumb: false  
 

widget1:
  title: "About"
  url: '/about/'
  # image: none
  text: "This week-long summer Institute will provide foundational knowledge, skills and resources to successfully advance 12 public humanities projects, increasing their longevity, visibility and impact. This will be followed by a year of further online training & support."

widget2:
  title: "Sessions"
  url: '/sessions/'
  # image: none
  text: "The curriculum features a mix of case studies of model projects, technical training and interactive workshops & discussion to strengthen relationships & collaborations, create sustainable digital projects, and develop practical knowledge of methods and tools."

widget3:
  title: "Instructors"
  url: '/instructors/'
  # image: none
  text: 'The Institute sessions will be led by more than 20 experienced academics and community partners, offering a breadth of complementary skill sets and areas of expertise that will provide participants rich opportunities for learning and  engagement.'




#
# Use the call for action to show a button on the frontpage
#
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

callforaction:
  url: /apply/
  headline: Apply
  text: The Institute invites one academic and one community partner per project to apply by Monday, January 31, 2022.
  alert_text: Apply
  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


<!--
page content
-->