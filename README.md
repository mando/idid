# I Did

## About

When I do stuff, I like to remember it.

When I want to remember stuff, I use `i did`.

## Install

Put `i` some place in your path.  I like `$HOME/bin`, but do what you like.

## Use

    $ i "did a bunch of stuff"
    Yeah you did!

    $ i did
    >> did a bunch of stuff

    $ pbpaste
    did a bunch of stuff

    $ i "did some more stuff"
    Yeah you did!

    $ i did
    >> did a bunch of stuff, did some more stuff

    $ pbpaste
    did a bunch of stuff, did some more stuff

There's really only 2 modes to `i`: doin' stuffs and seeing what you did.

    $ i "totes wrote this cool thing!"
    Yeah you did!

This will add "totes wrote this cool thing!" to a timestamped text file in $HOME/.idid.  Don't like that?  HAX IT!

    $ i "deployed all my shiz"
    Yeah you did!

This will append "deployed all my shiz" to the same timestamped text file.  After midnight, tho, you're getting a new text file.

    $ i did
    >> totes wrote this cool thing!, deployed all my shiz

Now you've got a list of everything you did, all comma-separated just like you like.  Oh, and because you're so very nice?

    $ pbcopy
    totes wrote this cool thing!, deployed all my shiz

That's right - it's all up in your pasteboard (sorry, OS X only).

## Why?

I wrote `i` because I needed something a little nicer than the nvalt hack I was using before.  I like to keep track of what I'm doing during the day, and at the end when we do our daily standups I'm all BAM! paste them shiz and DONE.
