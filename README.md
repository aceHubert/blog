# hubert's blog

> Ported Theme of [Hux Blog](https://github.com/Huxpro/huxpro.github.io), Thank [Huxpro](https://github.com/Huxpro) for designing such a flawless theme.
> 
> updated from BeanTech theme created by [YuHsuan](http://beantech.org)


<br/>

#### Some local command:
```bash
yarn generate # hexo clean && hexo generate
yarn serve  # hexo serve
yarn deploy # yarn generate && hexo deploy
```

#### Some hexo command:
```bash
hexo new post "<post name>" # you can change post to another layout if you want
hexo clean && hexo generate # generate the static file
hexo serve # run hexo in local environment
hexo deploy # hexo will push the static files automatically into the specific branch(gh-pages) of your repo!
```

#### theme config in root

```yml
theme: beantech
theme_config:
  index-title: Hi, this's Hubert!  # index page title
  index-title-color: "#333" # index page title color  
  show_count: true # category show count
  menu:
    archives: /archive
    # categories: /categories
    # tags: /tags
    aboutme: /about
  post-widgets: # post bottom widgets display when root config set sidebar false
    # -  featured-tags
    # -  friends
  page-widgets: # page bottom widgets display when root config set sidebar false
    # -  featured-tags
    # -  friends

```

#### post/page config in header
> index-title-color is in the theme_config 
```yml
title-color: "#333" # title color
display: false # show it in the index page
```
