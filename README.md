hanmarookim.github.io
==============

> [GitHub Pages] & [Jekyll] / Theme - [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) 사용

### 설치

1. git fetch or pull or clone
2. [Jekyll] 설치

```console
$ git clone git@github.com:hanmarookim/hanmarookim.github.com.git
$ cd hanmarookim.github.com
$ bundle install
```

### 실행(로컬)

```
$ bundle exec jekyll serve
```

### 배포(발행)

```
$ git commit -m '...'
$ git push origin master
````

### 글 쓰기

1. `_posts` 디렉토리에 `yyyy-mm-dd-slug.md` 파일로 복사(or 이동).
 - slug: 해당 포스트의 고유 키 / URL의 일부
 - yyyy,mm,dd: 발행 년,월,일.
2. 파일 상단에 [front matter] 작성
 - layout: post # `page` 사용 시 정적 페이지
 - title: '제목' 
 - author: `hanmaroo.kim` 
 - category: `[category-name]` 
 - date: `YYYY-MM-DD HH:MM:SS` 
 
혹은 local jekyll 서버 구동시:
1. `localhost:4000/admin/`에 `New Post(Page)` 클릭 후 작성

### 카테고리 등록

1. `_categories` 디렉토리에 `category-name.md` 추가
2. 파일 상단에 [front matter] 작성
 - layout: category
 - name: `category-name`
 - title: ... # 구체적인 설명
