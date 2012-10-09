# Octopress plugin for Sublime Text 2 #
*used by top ramen coders*
## Pitfalls

Plugin assumes that you have your octopress folder opened in the file pane. For now, 'octopress folder' means 'first folder with Rakefile in it' :) 

OS X Pitfall: Octopress uses rake, which uses ruby. If you run Sublime Text 2 from the GUI (dock/launchpad/etc.) it may not see your bash environment, including your usual ruby path. To fix this you need to add necessary environment variables to `~/.MacOSX/environment.plist`. It could be done manually or using a simple script like [this one](http://hints.macworld.com/article.php?story=20040715133738459). The changes to the environment symbol definitions will become active the next time you log in.

## Copy your public key to ramencoder.com ## ##
```
ssh-copy-id ramencoder@ramencoder.com
```

TODO: add manually add instruction

## Use ##

Command + Shift + P: 
  Octopress: New post
  Octopress: New wiki
  Octopress: Deploy
Also can be accessd from Tools -> Octopress