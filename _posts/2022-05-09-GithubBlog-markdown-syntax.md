---
title: '마크다운 문법(Syntax) 정리본 v1.0'
excerpt: 마크다운 문법(Syntax) 정리본 v1.0
categories:
  - Github Blog
tags:
  - - Blog
    - markdown
toc: true
toc_sticky: true
date: 2022-05-09
last_modified_at: 2022-05-09
published: true
---

# 마크다운 문법(Syntax) 정리본 v1.0

필자가 손에 익히고자 정리하는 마크다운 문법 정리본 v1.0

하나씩 필요한 게 있을  때마다 해당 포스트에 업데이트하며 버전 업데이트를 할 예정입니다.



## 1. 제목(Header)

제목은 `<h1>` 부터 `<h6>` 까지 사용할 수 있다. 숫자가 커질수록 글자 크기는 작아진다.

```markdown
# 제목 h1
## 제목 h2
### 제목 h3
#### 제목 h4
##### 제목 h5
###### 제목 h6
```

* 예시

# 제목 h1

## 제목 h2

### 제목 h3

#### 제목 h4

##### 제목 h5

###### 제목 h6



# 2. 인용문 사용해서 텍스트 박스 강조하기

인용문을  사용할 때 `>` 을 사용한다. 인용문 안에서 하나 더 들여써서 인용문을 사용 시 `>>`을 사용하면 된다.

```markdown
> **NOTE: ** this is note content.
> note example.
>> 들여쓰기 예시
```

* 예시

  > **NOTE: ** This is note content.
  >
  > note example.
  >
  > > 들여쓰기 예시



# 3. 구분선

구분선 종류는 총 3가지이다. 뭘 써도 어차피 같은 구분선이라서 편한걸로 사용하면 된다.

```markdown
---
***
___ (언더바)
```

* 예시

  ---

  ***

  ___

  

# 4. 폰트 색상, 형광펜 칠하기

폰트 색상을 변경하거나 하이라이트 효과를 줄때는 `html` 을 사용해야한다. 

원하는 색상을 더 다양하게 사용하고 싶으면 color에 RGB 값을 넣어줘도 된다.

> **RGB 색상표 사이트** 
>
> [https://www.color-hex.com/](https://www.color-hex.com/)



```markdown
<span style="color: red">red font</span>
<span style="color: blue">blue font</span>
<span style="color: yellow">yellow font</span>
<span style="color: green">green font</span>
<span style="color: #9370DB">rgb color #9370DB</span>

<span style="background-color: red">red font</span>
<span style="background-color: blue">blue font</span>
<span style="background-color: yellow">yellow font</span>
<span style="background-color: green">green font</span>
<span style="background-color: #9370DB">rgb color #9370DB</span>
```

* 폰트 색상 예시

  <span style="color:red">red font</span>

  <span style="color: blue">blue font</span>
  <span style="color: yellow">yellow font</span>
  <span style="color: green">green font</span>

  <span style="color: #9370DB">rgb color #9370DB</span>

* 형광펜 예시

  <span style="background-color: red">red font</span>
  <span style="background-color: blue">blue font</span>
  <span style="background-color: yellow">yellow font</span>
  <span style="background-color: green">green font</span>
  <span style="background-color: #9370DB">rgb color #9370DB</span>

  

# 5. 이모지 사용하기

마크다운에서도 이모지 사용이 가능하다. 이모지 종류 표는 추후 정리해서 포스팅 할 예정! :wink:

```markdown
:rocket:
:laughing:
:heart:
```

* 예시

  :rocket:

  :laughing:

  :heart:



## 참고1. 접기/펼치기 토글 버튼

타사 블로그처럼 토글 버튼을 이용해서 글 내용을 `html`코드를 이용해 접기/폅기 할 수 있다. 

```markdown
<details>
<summary>접기/펼치기 버튼</summary>
<div markdown="1">
접기 펼치기
예시입니다!
</div>
</details>
```

* 예시

  <details>
  <summary>접기/펼치기 버튼</summary>
  <div markdown="1">
  접기 펼치기
  예시입니다!
  </div>
  </details>

