# hexo-theme-mono

*A minimalist Hexo theme*

The design is borrowed from [hexo-theme-icalm](https://github.com/nameoverflow/hexo-theme-icalm).

<a href="https://problem233.github.io/posts/my-own-hexo-theme/">中文文档</a>

## Preview

![demo](https://user-images.githubusercontent.com/13145126/36340501-22f5f134-1419-11e8-9680-a3dfb19fb51c.png)

Live demo:

- [My blog](https://problem233.github.io/)

## Browser Support

Support: Edge 16+, Firefox ESR+, Chrome 49+, Safari 10+, Opera 36+.

Doesn't support any version of IE.

Besides, the theme requires node version to be `>= 5.0.0`.

## Installation

```shell
$ npm i --save hexo-renderer-jade
$ git submodule add https://github.com/problem233/hexo-theme-mono.git themes/mono
```

Updadte:

```shell
$ git submodule update --remote
```

## Customize

To customize config, copy `_config.yml` to `<site root dir>/source/_data/mono.yml`, then edit it.

To customize style, edit `<site root dir>/source/css/custom.css`. If you need to overwrite theme's default, don't forget to add `!important`.

Example: [the source of my blog](/problem233/blog)

## Add tags page

Add a file `<site root dir>/source/tags/index.md` with following content:

```markdown
---
title: Tags
layout: tags
---
```

## License

WTFPL
