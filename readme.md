```~~raw~~
course https://frontendmasters.com/courses/getting-started-css/
website https://gettingstartedwith.css.education/

https://www.internetfundamentals.com/watch/
https://computer.howstuffworks.com/dns.htm
webhosts good - siteground, inmotion hosting, DigitalOcean
stay away from godaddy, bluehost, hostgator
file transfer thru FTP 
domain name registrar - namecheap 
https://www.namecheap.com/
https://www.nameboy.com/
https://codepen.io/

https://gettingstartedwith.css.education/index.html
https://gettingstartedwith.css.education/ch1.html

https://color.adobe.com/explore
https://fonts.google.com/
https://fonts.google.com/?query=oxygen
https://www.fontpair.co/
https://www.internetfundamentals.com/watch
https://frontendmasters.com/bootcamp
https://frontendmasters.github.io/bootcamp

css variables 
https://frontendmasters.com/courses/css-variables/
border box
https://css-tricks.com/box-sizing/


https://frontendmasters.github.io/bootcamp/

by default, headings have margin assigned to them. 1em = relative unit for all headings

margin in css, two elements with margin 1rem in vertical direction, they will collapse to 1rem(if they are 1 rem, 2rem, 2rem wins in margin-land)
padding, two elements with margin 1rem, distance 2rem

when you set up links inside elements/text like p, display underline by default, turn off underline on hover; 10% of population is color-blind, hence have something other than color. Accessibility

on nav-bar, fine to turn off underline, we have position in space, markup to indicate that it is link

hamburger menu with just css in https://frontendmasters.com/courses/advanced-css-layouts/

https://fontawesome.com/icons
for icons

loading as icon requires https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css
where as svg doesn't

if target audience knows icons, use only icons, otherwise use icons+text

use only icons/svgs
aria-hidden = true, hide from screen-readers
sr-only = read by screen readers only

The <a> element is inline by default. Inline means that it's only as big as the content inside of it. When we change it to block, the size changes from the size of the content to the size of its parent element (the LI). That gives us a much larger clickable area than we had with the inline <a> by itself.

Button is about executing something = submitting a form. opening a modal window, 
Link is about, go to another page, page on same website, or another website

To bring a brand/attention, make Resume a button

responsive design
old: https://frontendmasters.com/courses/archive/css-grid-flexbox-v2/
https://frontendmasters.com/courses/css-grid/


<small> like <b> and <i> disappeared in HTML4, back in HTML5.
used for small print, disclaimers, copyright

.html > type ! > press tab 


To implement a gradient, use border-image. works in chrome, firefox, but not in safari
so use div with a class of gradient, small height to generate the line
use https://cssgradient.io/ to generate gradient. Use #ff17e4 as the starting color and #86fbfb as the ending color for this exercise, stops at 35, 68, angle at 90deg

putting two items next to each other using flexbox and css grid 
grid can overlap one cell with another on top of each other, but felxbox can not.

Since we have img on the left and text on the right, 
we cant switch in html, as in mobile view, text first and img next.
so, we use order property on the desktop/tablet view

text-align is a inherited property, that can cascade thru all of the text

grid-column to span from one col to another, but puts it on another row.
so use grid-row to align on same row

extras:
How to create a page for projects on github
https://pages.github.com/
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Available at: https://bhaskar1312.github.io/fm-getting-started-with-css/
