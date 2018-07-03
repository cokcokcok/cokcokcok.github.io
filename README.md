# posting 방법

## blog
~~~
---
title: 제목 입력
layout: post
date: 포스팅 날짜
image: 이미지 경로 입력
headerImage: 헤드 라인에 이미지르 보여줄지 여부 결정(T/F)
tag: 포함 하고 있는 내용의 요소 입력
ex)
- markdown
- elements
category: blog
author: 작성자의 이름 등록
description:
---
포스팅 내용 삽입
~~~

## projects
~~~
---
title: 제목 입력
layout: post
date: 포스팅 날짜
image: 이미지 경로 입력
headerImage: 헤드 라인에 이미지르 보여줄지 여부 결정(T/F)
tag: 포함 하고 있는 내용의 요소 입력
ex)
- markdown
- elements
category: project
author: 작성자의 이름 등록
description:
---
포스팅 내용 삽입
~~~

## 링크
**인라인 링크**
마크다운 | 결과
|:-------:|:----:|
\[google](https://google.co.kr) | [google](https://google.co.kr)
**URI**
마크다운 | 결과
|:-------:|:----:|
\<https://google.co.kr> | <https://google.co.kr>
**내부 링크**
마크다운 | 결과
|:-------:|:----:|
\[blog](#blog) | [blog](#blog)

## 이미지 삽입
**인라인 이미지**
마크다운 | 결과
|:-------:|:----:|
\!\[사진 설명](/assets/images/markdown.jpg) | ![사진](/assets/images/markdown.jpg)
**링크 이미지**
마크다운 | 결과
|:-------:|:----:|
\!\[사진설명](https://avatars1.githubusercontent.com/u/9919?s=200&v=4) | ![github](https://avatars1.githubusercontent.com/u/9919?s=200&v=4)



<!-- <p align="center">
    <h2 align="center">Indigo Minimalist Jekyll Template - <a href="http://sergiokopplin.github.io/indigo/">Demo</a> · <a href="https://travis-ci.org/sergiokopplin/indigo"><img src="https://camo.githubusercontent.com/5393485b732749b3499264168fa8af60166071e8/68747470733a2f2f7472617669732d63692e6f72672f73657267696f6b6f70706c696e2f696e6469676f2e7376673f6272616e63683d67682d7061676573" alt="Build Status" data-canonical-src="https://travis-ci.org/sergiokopplin/indigo.svg?branch=gh-pages" style="max-width:100%;"></a></h2>
</p>

<p align="center">This is a simple and minimalist template for Jekyll for those who likes to eat noodles.</p>

***

<p align="center">
    <b><a href="README.md#what-has-inside">What has inside</a></b>
    |
    <b><a href="README.md#setup">Setup</a></b>
    |
    <b><a href="README.md#settings">Settings</a></b>
    |
    <b><a href="README.md#how-to">How to</a></b>
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/sergiokopplin/indigo/gh-pages/assets/screen-shot.png" />
</p>

## What has inside

- [Jekyll](https://jekyllrb.com/), [Sass](http://sass-lang.com/) ~[RSCSS](http://rscss.io/)~ and [SVG](https://www.w3.org/Graphics/SVG/)
- Tests with [Travis](https://travis-ci.org/)
- Google Speed: [98/100](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fsergiokopplin.github.io%2Findigo%2F);
- No JS. :sunglasses:

## Setup

0. :star: to the project. :metal:
2. Fork the project [Indigo](https://github.com/sergiokopplin/indigo/fork)
3. Edit `_config.yml` with your data (check <a href="README.md#settings">settings</a> section)
4. Write some posts :bowtie:

If you want to test locally on your machine, do the following steps also:

1. Install [Jekyll](http://jekyllrb.com), [NodeJS](https://nodejs.org/) and [Bundler](http://bundler.io/).
2. Clone the forked repo on your machine
3. Enter the cloned folder via terminal and run `bundle install`
4. Then run `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
5. Open it in your browser: `http://localhost:4000`
6. Test your app with `bundle exec htmlproofer ./_site`
7. Do you want to use the [jekyll-admin](https://jekyll.github.io/jekyll-admin/) plugin to edit your posts? Go to the admin panel: `http://localhost:4000/admin`. The admin panel will not work on GitHub Pages, [only locally](https://github.com/jekyll/jekyll-admin/issues/341#issuecomment-292739469).

## Settings

You must fill some informations on `_config.yml` to customize your site.

```
name: John Doe
bio: 'A Man who travels the world eating noodles'
picture: 'assets/images/profile.jpg'
...

and lot of other options, like width, projects, pages, read-time, tags, related posts, animations, multiple-authors, etc.
```

## How To?

Check the [FAQ](./FAQ.md) if you have any doubt or problem.

---

[MIT](http://kopplin.mit-license.org/) License © Sérgio Kopplin -->
