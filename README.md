== * Git-Ruby Is Not Maintained *

The Git-Ruby project is no longer maintained by me.  I will leave it up here for now, but almost all of this code has since been incorporated into the Grit project (http://github.com/schacon/git-ruby) and works much, much better.  If you're interested in using Git from Ruby, please check out Grit (specifically the schacon/grit fork) - it does as much as it can from Ruby and falls back to system calls if it needs to.  The API is different, but the project is being actively maintained.

== Git Library for Ruby

A pure ruby implementation of Git

= Homepage

The Git-Ruby homepage is currently at : 

http://jointheconversation.org/gitruby

Git public hosting of the project source code is at:

http://github.com/schacon/gitruby

= Roadmap

Many of the simple read-only operations have already been
moved to pure ruby.

= Gitr

I have included a command line pure-ruby git client called 'gitr'

The following commands are available - they all will run in pure ruby, without forking out the the git binary.
In fact, they can be run on a machine without git compiled on it.

commands: log
          log-shas
          cat-file (treeish)
          rev-parse (treeish)
          branches
          ls-tree (tree)
          

= Examples

Here are a bunch of examples of how to use the Git-Ruby package. 

First you have to remember to require rubygems if it's not.  Then include the 'git-ruby' gem.

   require 'rubygems'
   require 'git-ruby'

