jquery.bootstrapPopover
=======================

What
----

A plugin to facilitate easy showing of the popover dialogs from Twitter's new
bootstrap css library.
  
It opens a targeted element's contents in the popover when you click on the
referenced anchor tag, and will close when you click again. 
  
It is also window resize concious. It will stick to the anchor tag.
  

Show Me
-------

Somewhere in your document:

    <a class="bootstrap-popover" href="#element_containing_popover_contents" title="My Popover Title">Click me fellas!</a>

In your `<head>`:

    <script type="text/javascript" charset="utf-8">
        $(function() {
            $('a.bootstrap-popover').bootstrapPopover();
        });
    </script>


But I Need Options!
-------------------

You want em', you got em'. Just pass them into the initial call as a JSON
object.

Options:

    {
    fade_out_speed: "fast",
    fade_in_speed: "fast",
    
    before_open: function() { return; },
    after_open: function() { return; },
    before_close: function() { return; },
    after_close: function() { return; },
    
    tooltip_mode: false,
    
    popover_html: " \
    <div class=\"popover left\" style=\"position:absolute;top:-10000;left:-10000;\"> \
      <div class=\"arrow\"></div> \
      <div class=\"inner\"> \
        <h3 class=\"title\"></h3> \
        <div class=\"content\"> \
        </div> \
      </div> \
    </div>"
    }

  

Why
---

Because we all know that it takes 7 elephants to row a canoe across the desert
on peanut butter and jelly sandwiches when Justin Beiber is a pear tree.
  

How
---

Create an anchor tag, the href element should be a css selector to a div
holding the content for the popover. The title attr on the anchor tag should be
the title of the popover.
  
see index.html for more info.
  

Bugs
----

Fork it, and fix 'em. I did this as sort of a quick and dirty script. It's
helping me right now. I hope it can help you as well. If you see something that
needs to be fixed, file an issue above. You can also let me know on [twitter](http://twitter.com/philipthrasher "FOLLOW ME NOW MORTAL").

Who
---

Why, @pthrasher of course! You can [follow](http://twitter.com/philipthrasher "FOLLOW ME NOW MORTAL") me on twitter, or shoot me a message
here on github.
