Custom Kibi Icons
=================

Made thanks to awesome project [fontcustom](https://github.com/FontCustom/fontcustom) 

#### To regenerate:    
 
* add your vector *.svg file to **vectors** folder
* follow the instructions at [fontcustom](https://github.com/FontCustom/)


```
fontcustom compile -F
fontcustom watch vectors
```

last time generated with fontcustom version 2.0.0

#### on OSX catalina follow this instructions 

```
brew tap bramstein/webfonttools
brew install woff2 sfnt2woff eot-utils
brew cask install fontforge
sudo gem install fontcustom

and edit your PATH to include both Ruby and FontForge paths:
/usr/local/lib/ruby/gems/2.6.0/bin
/Applications/FontForge.app/Contents/Resources/opt/local/bin

in my .zshrc I have (may need cleaning):
export PATH=$HOME/bin:/usr/local/lib/ruby/gems/2.6.0/bin:/Applications/FontForge.app/Contents/Resources/opt/local/bin:/usr/local/bin:/usr/local/sbin:/Users/MYUSER/.composer/vendor/bin:/usr/local/opt/ruby/bin:/$PATH
```