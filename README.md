<h1 align="center">Mokusei</h1>
<p align="center">Mokusei is a dark Hexo theme that is dedicated to creating a quiet reading environment.</p>

[Preview](https://blog.shijukun.com)   
[中文文档](#) 

## Feature

* Three-column layout
* Comment system (Disqus)
* Icon customization
* Social account
* Article directory (rolling monitor)
* Focus mode (hidden sidebar)
* Article cover
* Particle animation
* Multi-language

## Installation

```
git clone https://github.com/shijuuu/hexo-theme-mokusei.git themes/mokusei
```
Modify the <code>theme</code> option of <code>_config.yml</code> in the root directory of the blog to mokusei

## Update

```
cd themes/mokusei
git pull
```

## Theme configuration

```yaml
# site
name: Site name    
description: Site description
favicon:
banner: http://plo9kpis3.bkt.clouddn.com/head.jpg
rss:  

# navigation
menu:
  Home:
    url: /
    icon: home
    iconType: fa
  Archives:
    url: /archives/
    icon: archive
    iconType: fa

# Social account
account:
  github:
    url: /
    icon: github
    iconType: fa
  mail:
    url: /
    icon: envelope
    iconType: fa
  twitter:
    url: /
    icon: twitter
    iconType: fa

  # Comment system
comment:
  disqus:
    shortname:  
```

## Common problem


### How to open the article directory?

Edit the md file of the article and add a line of code <code>tocifs: true</code> to the header are, reference example:

```
---
title: article title
date: 2019-01-21 09:28:48
tocifs: true
---
```

### How to set the article cover?

Edit the md file of the article, add a piece of code <code>photos</code> in the header area, reference example:

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

## Feedback

[ISSUE](https://github.com/shijuuu/hexo-theme-mokusei/issues/)
