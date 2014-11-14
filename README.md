# Modernist

> Theme for [Hexo]. Based on [modernist theme] for GitHub Pages.

You can check the [Demo].

## Install

```
git clone git@github.com:paincompiler/modernist-paincompiler.git 
```

**Modernist requires Hexo 2.4 and above.**

## Enable

Modify `theme` setting in `_config.yml` to `modernist`.

## Configuration

First you  must create an `about` page to fit. You can run this command:

``` 
# hexo new page 'about'
```
Then you can modify the `_config.yaml` file.

``` 
yaml

# Header
menu:
  Home: /
  Archives: /archives
about: /about

# Content
archive_date_format: MMM DD
fancybox: true

# Comment Plugin
duoshuo_shortname:

# Miscellaneous
google_analytics:
favicon: /favicon.ico
```

- **menu** - Navigation menu
- **about** - about page
- **archive_date_format** - Date format in archives page.
- **fancybox** - Enable [Fancybox]
- **duoshuo_shortname** - [Duoshuo] ID
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path

[Hexo]: http://zespia.tw/hexo/
[modernist theme]: https://github.com/orderedlist/modernist
[Demo]: http://blog.paincompiler.us/
[Duoshuo]: http://duoshuo.com
[Fancybox]: http://fancyapps.com/fancybox/
