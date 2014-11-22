##Powerbook
Powerbook is a script to set up a Mac OS X laptop ready for development.

###Manual setup

When all is complete, you'll need to setup iTerm2 color scheme manually, download SpaceGray theme from [iterm2colorschemes](http://iterm2colorschemes.com/) and then load it from the color tab in iTerm2, finally set the font to Source Code Pro for Powerline need it by the [agnoster](https://gist.github.com/agnoster/3712874) theme for zsh.

You'll get something like this:

![image](http://f.cl.ly/items/160A0W1u2D0K1A3E3y0G/iTerm2.png)


it will match The Space Gray theme for ST2 (pre-isntalled for you)

![image](http://f.cl.ly/items/2D2Q1Q0A3l2G0M3R0M0g/spacegray.png)

###Install

run the script:

```bash
$ bash -c "$(curl -fsSL raw.github.com/rauluranga/powerbook/master/bin/install)"
```

###Features

####Automatic software installation:   

- [homebrew](http://brew.sh/)
- [oh my zsh](https://github.com/robbyrussell/oh-my-zsh)
- [ruby 2.1.2](https://www.ruby-lang.org/en/)
- [My dotfiles](https://github.com/rauluranga/dotfiles)

####Command-line tools using homebrew:   

- [cask](https://github.com/caskroom/homebrew-cask)
- [git-flow](https://github.com/nvie/gitflow)
- [gh](https://github.com/jingweno/gh)
- [the_silver_searcher](https://github.com/ggreer/the_silver_searcher)
- [tmux](http://tmux.sourceforge.net/)
- [tree](http://mama.indstate.edu/users/ice/tree/)

####Ruby gems:   

- [bundler](http://bundler.io/)
- [cocoapods](http://cocoapods.org/)
- [powder](https://github.com/Rodreegez/powder)
- [rake](https://github.com/jimweirich/rake)
- [homesick](https://github.com/technicalpickles/homesick)
- [librarian-chef](https://github.com/applicationsonline/librarian-chef)
- [chef](https://github.com/opscode/chef/)

####OS X Applications

- [alfred](http://www.alfredapp.com/)
- [appcode](http://www.jetbrains.com/objc/)
- [caffeine](http://lightheadsw.com/caffeine/)
- [dropbox](https://www.dropbox.com/)
- [firefox](http://www.mozilla.org/en-US/firefox/new/)
- [github](https://mac.github.com/)
- [google-chrome](https://www.google.com/intl/en/chrome/browser/)
- [google-drive](https://drive.google.com/)
- [iterm2](http://www.iterm2.com/)
- [onepassword](https://agilebits.com/onepassword)
- [skype](http://www.skype.com/en/)
- [spotify](https://www.spotify.com/)
- [the-unarchiver](http://wakaba.c3.cx/s/apps/unarchiver)
- [transmission](https://www.transmissionbt.com/)
- [vlc](http://www.videolan.org/vlc/index.html)

#### Quick Look plugins

- [qlcolorcode](https://code.google.com/p/qlcolorcode/)
- [qlstephen](https://github.com/whomwah/qlstephen)
- [qlmarkdown](https://github.com/toland/qlmarkdown)
- [qlprettypatch](https://github.com/atnan/QLPrettyPatch)
- [quicklook-csv](https://github.com/p2/quicklook-csv)
- [quicklook-json](http://www.sagtau.com/quicklookjson.html) 
- [provisionq](https://github.com/ealeksandrov/ProvisionQL)

#### Fonts

- [source-code-pro](http://blog.typekit.com/2012/09/24/source-code-pro/)
- [dejavu-sans-mono-for-powerline](https://github.com/Lokaltog/powerline-fonts/tree/master/DejaVuSansMono)
- [font-inconsolata-for-powerline](https://github.com/Lokaltog/powerline-fonts/tree/master/Inconsolata)
- [font-inconsolata-dz-for-powerline](https://github.com/Lokaltog/powerline-fonts/tree/master/InconsolataDz)
- [font-sauce-code-powerline](https://github.com/Lokaltog/powerline-fonts/tree/master/SourceCodePro)

###Known Issues

- In some cases fonts instalation may fail, this because the [Caskroom-fonts](https://github.com/caskroom/homebrew-fonts) is a pre-release software, if this happen to you, just run ```$ brew cask install font-name``` for every font listed in the FontFile, it should work as expected.
