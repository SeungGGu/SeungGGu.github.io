---
# Header
title: "깃 허브 블로그 첫 번째 포스팅 md 언어에 대해 알아보자"
excerpt: "마크다운 문법을 이용해 md파일을 작성하여 Github blog에 포스팅 해보자."
name: SeungGGu
writer: SeungGGu
categories: [블로그, Git 블로그] # [메인 카테고리, 서브 카테고리]
tags:
  - [Git Blog, jekyll theme, Github, Git, markdown, Posting, MarkDown]

toc: true
toc_sticky: true

date: 2024-05-28
last_modified_at: 2024-05-28

# --- 아래 부터 content
---
# MD에 관한여 알아보자

## 제목

- `<h1>`,`<h2>`,`<h3>`,`<h4>`,`<h5>`,`<h6>` 태그로 변환되는 제목을 표현

```markdown
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```

## 수평선

- `<hr/>`와 동일한 결과
- `-`,`*`,`_`을 세개를 나열하여 수평선을 만듬

```markdown
***
---
___
```

## 주석

- 주석은 출력결과에 노출이 안된다
- 주석을 하고 싶은 줄에 Ctrl + / 을 누르면 된다

```markdown
<!--
주석 기능
-->
```

## 강조

- 기울임: `*기울여진 텍스트*` 또는 `_기울여진 텍스트_`
- 두껍게: `**굵은 텍스트**` 또는 `__굵은 텍스트__`
- 취소선: `~~취소선~~`
- 밑줄: `<u>밑줄된 텍스트</u>`

````markdown
*기울임* 혹은 _기울임_
**두껍게** 혹은 __두껍게__
~~취소선~~
<u>밑줄</u>
````

## 목록

- `<ol>`, `<ul>`, `<li>` 태그로 변환되는 '목록(List)'을 표현
  - `<ol>` 은 `1. ` 으로 시작하는 항목
  - `<ul>` 은 `-`,`+`,`*` 으로 시작하는 항목
  - 들여쓰기를 통해 하위 목록 생성

### markdown 코드문

```markdown
1. 항목 1
2. 항목 2
   1. 하위 항목 1
   2. 하위 항목 2
3. 항목 3

* 순서가 없는 항목
  * 순서가 없는 항목
    * 순서가 없는 항목
```
### 결과

1. 항목 1
2. 항목 2
   1. 하위 항목 1
   2. 하위 항목 2
3. 항목 3

* 순서가 없는 항목
  * 순서가 없는 항목
    * 순서가 없는 항목

## 링크

`<a>`로 변환되는 '링크(Links)'를 표현
```markdown
[사이트 이름](주소)
[사이트 이름](주소 "설명")
[사이트 이름][참조]

[참조]: 링크
[참조]: 링크 "설명"
```
- 예시

```markdown
[GOOGLE](https://google.com)

[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

[Dribbble][Dribbble Link] #참조

[GitHub][1] #참조

구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>

[Dribbble Link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"
```

## 이미지

- 이미지를 사용하기 위해선 아래의 문법을 사용한다
- `![사진이름](사진경로)`

```markdown
![Minion](http://octodex.github.com/images/minion.png)
```

- 출력결과

![Minion](http://octodex.github.com/images/minion.png)

나중에 블로그 포스팅을 할때 MarkDown 언어에 대해 궁금한게 더 생긴다면 이어서 포스팅하겠다.