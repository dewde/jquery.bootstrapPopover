jquery.bootstrapPopover
=======================

What
----

A plugin to facilitate easy showing of the popover dialogs from Twitter's new
bootstrap css library.
  
It opens a targeted element's contents in the popover when you click on the
referenced anchor tag, and will close when you click again. 
  
It is also window resize concious. It will stick to the anchor tag.
  

Why
---

I wanted a quick and dirty way to do this, no one else made it yet.
  

How
---

Create an anchor tag, the href element should be a css selector to a div
holding the content for the popover. The title attr on the anchor tag should be
the title of the popover.
  
see index.html for more info.
