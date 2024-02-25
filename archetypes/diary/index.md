---
title: "{{ replace .Name "-" " " | title }}" # Title of the blog post.
date: {{ .Date }} # Date of post creation.
description: "Article description." # Description used for search engine.
featured: true # Sets if post is a featured post, making appear on the home page side bar.
draft: true # Sets whether to render this page. Draft of true will not be rendered.
toc: false # Controls if a table of contents should be generated for first-level links automatically.
abstract: "초록"
# menu: main
usePageBundles: true # Set to true to group assets like images in the same folder as this post.
featureImage: "/images/path/file.jpg" # Sets featured image on blog post.
featureImageAlt: 'Description of image' # Alternative text for featured image.
featureImageCap: 'This is the featured image.' # Caption (optional).
thumbnail: "/images/path/thumbnail.png" # Sets thumbnail image appearing inside card on homepage.
shareImage: "/images/path/share.png" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: false # Override global value for showing the figure label.
categories:
  - Diary
tags:
  - Tag_name1
  - Tag_name2
# comment: false # Disable comment if false.
showReadTime: false
---
> 시작멘트

| 제목      | 제작            | 배급     | 출시일          | 플랫폼                   | 리뷰플랫폼 |
| --------- | --------------- | -------- | --------------- | ------------------------ | ---------- |
| HiFi Rush | Tango Gameworks | Bethesda | 2023년 1월 23일 | Xbox Series X\|S <br> PC | PC         |

**Insert Lead paragraph here.**