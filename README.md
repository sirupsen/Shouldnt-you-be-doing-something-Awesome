# Shouldn't you be doing something Awesome?

Well of course you should, and now you can:

    $ ishouldbedoingsomethingawesome
    Do awesome.

Everybody has their limits:

    $ ineedtostopbeingawesome
    Stop doing awesome.

## What does it do?

It makes you productive, by limiting the sites you can go to in your period of `Awesome`.

## How do I block a site for my period of Awesome?

    $ blocksitewhenawesome time-wasting-site.com time-wasting-site2.com

## How does it work?

`shouldnt-you-be-doing-sometthing-awesome` `SSH` you into your own machine (instead of changing `/etc/hosts` which would require root access). All the blocked sites are in `~/.ssh/config.block` which temporarily replaces `~/.ssh/config`, whenever you should be doing something Awesome. `~/.ssh/config` allows you to modify hostnames; we can redirect `time-wasting-site.com` to `127.0.0.1:1337`. `127.0.1:1337` will simply tell you to stop wasting time, and start being awesome.

## Isn't this useless?

If you can handle not going to time-wasting sites without something like this, sure.

## Note on Patches/Pull Requests
 
* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a
  future version unintentionally.
* Commit, do not mess with rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2010 Sirupsen. See LICENSE for details.
