---
layout:
  - next
title: 2022
date: 2022-05-19 14:25:21
tags:
---
# What I setup 
- inital hexo blog
- seperate git repository
  - for static site public web
  - orginal hexo develop 
- change theme to NEXT

## How to start
1. Install nodejs
2. install npm ci
3. install hexo module
4. inital hexo project `hexo init blog`

## _config.yml
These are the setting I change
### change url
```
url: https://jakccl.github.io
root: /blog
```

### change deploy setting
```
deploy:
  type: git
  repo: https://github.com/jakccl/blog.git
  branch: main
```

## create page
- add about page
> hexo add page about

- add tags page
> hexo add page tags

- add categories
> hexo add page categories

## _config.yml for next theme
- add menu
```
menu:
  home: / || fa fa-home
  about: /about/ || fa fa-user
  tags: /tags/ || fa fa-tags
  categories: /categories/ || fa fa-th
  archives: /archives/ || fa fa-archive
```