hr
==

`<hr />` for your terminal


Tired of not finding things in your terminal because there's a lot of logs and
garbage? Tired of destroying the Enter key by creating a "void zone" in your
terminal so that you can see the error that you're trying to debug?

Use the old `<hr />` tag, but in your terminal. How? Allow me to explain:

## Setup

    $ curl https://raw.github.com/tgrochowicz/hr/master/dong > ~/bin/dong
    $ chmod +x ~/bin/dong

Note: You should have `~/bin` in your `$PATH` for this to work.

## How to use it?

    $ dong
    8=================================D # Till the end of your terminal window
    $

    $ hr *
    8*********************************D # Till the end of your terminal window
    $
    
That's it, no requirements, just pure old `bash` and `tput`, check the source,
it's free.

