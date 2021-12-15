---
layout: post
title: "Jekyll admin 추가"
date:   2021-12-05 20:34:09 +0900
categories: jekyll update
comments: true
---

jekyll이 설치되어있으면
Gemile 을 열어서 아래의 코드를 추가한다.

```
gem "jekyll-admin", group: :jekyll_plugins
```

터미널에서 아래의 코드를 실행 시킨 후 
```
bundle intall
```

서버 재가동
```
bundle exec jekyll serve
```

그리고 아래의 페이지로 접속하면 admin 페이지가 보인다 (간단~~ ^^)

http://localhost:4000/admin/