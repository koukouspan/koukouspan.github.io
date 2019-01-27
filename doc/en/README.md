<h1 align="center">Mokusei</h1>
<p align="center">Mokusei is a dark Hexo theme that is dedicated to providing a quiet reading environment</p>

[Preview](https://blog.shijukun.com)   

## Installation

```
git clone https://github.com/shijuuu/hexo-theme-mokusei.git themes/mokusei
```
Modify the <code>theme</code> option value in <code>_config.yml</code> located in the root directory of the blog to <code>Mokusei</code>

## Update

```
cd themes/mokusei
git pull
```

## Feature

* Three-column layout
* Comment system (Disqus)
* Icon customization
* Social account settings
* Article directory (rolling monitor)
* Focus mode
* Article cover
* Particle animation
* Multilingual (internationalization)

## Multi-language

The theme supports languages in 11 countries. The default language is Chinese.
Change the language, please modify the <code>language</code> option in <code>_config.yml</code> located in the root directory of the blog.

## Theme configuration

```yaml
# Site configuration
name: site name
description: site description
favicon:  Address bar icon
banner: head picture
rss:  
# Nav configuration
menu:
  Home:
    url: /
    icon: home
    iconType: fa
  Archives:
    url: /archives/
    icon: archive
    iconType: fa
# Account configuration
account:
  github:
    url: /
    icon: github
    iconType: fa
  twitter:
    url: /
    icon: twitter
    iconType: fa
# Comment system
comment:
  disqus:
    shortname:  
# Function switch
ifsparticle:  false   # Whether to display particle animation
# Child theme
childtheme: 0 # Switch child theme 0 -dark    1- light
```

## Theme feature configuration

### Open article directory

Edit the MD file of the article and add <code>tocifs: true</code> to the header as follows:

```
---
title: article title
date: 2019-01-21 09:28:48
tocifs: true
---
```

### Set article cover

Edit the MD file of the article and add <code>photos</code> to the header as follows:

```
---
title: article
date: 2019-01-21 09:28:48
photos:
- "image url"
---
```

## Reference

Refer to the <code>clean-blog</code> and <code>landscape</code> topics, thanks!

## Contribution

Looking forward to your contribution!

## Problem submission

[ISSUE](https://github.com/shijuuu/hexo-theme-mokusei/issues/)

## Other

The image material used in the theme is from the network. If you have violated your rights, please let us know.
