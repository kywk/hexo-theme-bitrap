# This theme was deprecated. If you like its style, use [biture](https://github.com/kywk/hexo-theme-biture) #

## hexo-theme-bitrap

A single column, widget-less minimalist theme for [Hexo], based on [Bootstrap] css framework.

Preview: [live demo](http://kywk.github.io/hexo-theme-bitrap) / [kywk.life](http://kywk.github.io/)


### Installation

#### Install

``` bash
$ git clone https://github.com/kywk/hexo-theme-bitrap.git themes/bitrap
```

#### Enable

Modify `theme` setting in `_config.yml` to `bitrap`.

#### Update

``` bash
cd themes/bitrap
git pull
```


### Configuration

``` yml
# Header
menu:
  home: /
  archive: /archive
  submenu:
    google: //google.com/
    yahoo:  //yahoo.com/

extmenu:
  github: //github.com/
  hexo: //zespia.tw/hexo/
  theme:
    Pithiness:  //github.com/okoala/hexo-theme-pithiness
    Phase:  //github.com/tommy351/hexo-theme-phase
    Collect:  //github.com/beforeload/hexo-theme-collect

rss:

# Content
excerpt_link: Read More

fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```
- **menu** - Main navigation menu, dropdown menu supported.
- **extment** - Extend menu at the right hand side, dropdown menu supported too.
- **rss** - RSS subscription link (change if using Feedburner)
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - KEEP IT 'true'
- **google_analytics** - Google Analytics ID


[Hexo]: http://zespia.tw/hexo/
[Bootstrap]: http://getbootstrap.com/
