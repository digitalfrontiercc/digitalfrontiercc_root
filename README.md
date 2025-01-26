This is the root repository for the [digitalfrontier.cc](https://digitalfrontier.cc/) wiki. This wiki uses [ikiwiki](https://ikiwiki.info/).

As GitHub pages is static, there are currently two ways to contribute:
* E-mail me with the contents, and I will make the changes on the wiki on this side. See the contributing page on digitalfrontier.cc for details.
* Make a local copy of the wiki on your laptop. This is slightly complicated and more work, so it is not the recommended method. 

First, install ikiwiki:
https://ikiwiki.info/download/

To make a local working copy, clone this repository:
* https://github.com/digitalfrontiercc/digitalfrontiercc_root

Then clone the following two into the "digitalfrontiercc_root" directory:
* https://github.com/digitalfrontiercc/digitalfrontiercc
* https://github.com/digitalfrontiercc/digitalfrontiercc.github.io

Now you should have a director "digitalfrontiercc_root", with inside "digitalfrontiercc", "digitalfrontiercc.github.io" and "digitalfrontiercc.setup"

Make all changes to the wiki by editing .mdwn files in "digitalfrontiercc". To build, run 
```
ikiwiki digitalfrontiercc digitalfrontiercc.github.io --refresh
```
in the root folder. When done with all your changes, commit all your changes to both branches and make pull requests for both. 
(I know, this could've been done better. I'll get to it at some point)

Refer to these pages if you run in to problems:
https://ikiwiki.info/tips/github/
https://ikiwiki.info/tips/laptop_wiki_with_git/
