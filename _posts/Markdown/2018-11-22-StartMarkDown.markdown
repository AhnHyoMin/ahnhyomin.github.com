---
layout: post
type: post
title: "MarkDown 시작하기!"
date: 2018-11-22 18:43:59
published: true
comments: true
categories: [Markdown]
---


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY2NjI3NDJdfQ==
-->

# <center> 마크다운(Markdown) 시작하기  </center>

<a name="Section_1"></a>
### 마크다운(Markdown) 이란?

마크다운(Markdown)은 2004년 존 그루버(John Gruber)와 아론 스워츠(Aaron Swartz)에 의해 개발된 마크업 언어 이다.  
간단한 특수기호와 문자로 이루어진 마크다운의 문법을 이용하면, HTML과 같은 복잡한 포맷이 없어도 구조적인 웹문서를 빠르게 작성할수 있다. 또한 마크다운을 이용해 작성된 문서는 HTML 또는 PPT와 같은 다른 문서 형태로도 손쉽게 변환이 가능하다.


----


### 마크다운을 사용하는 주요 프로그램

* 워드 프레스 (WordPress)
* 깃헙 (Github)
* 레딧 (Reddit)
* 텀블러 (Tumblr)
* 트렐로 (Trello)
* 스팀잇 (Steemit)
* 디스코드 (Discord)
* 스택오버플로우 (Stackoverflow)


---

### 마크다운 작성 편집기

* 아톰 (Atom - PC)
* 스택에딧(Stackedit - PCWeb, Android)

----

### 문법

#### 제목  
  - **문법**
```
# 제목 1        == <h1></h1>
## 제목 2       == <h2></h2>
### 제목 3      == <h3></h3>
#### 제목 4     == <h4></h4>
##### 제목 5    == <h5></h5>
###### 제목 6   == <h6></h6>
```

    - 결과
# 제목 1  
## 제목 2  
### 제목 3  
#### 제목 4  
##### 제목 5  
###### 제목 6  


#### 텍스트 스타일  
  - **볼드 (Bold)**  
```
**볼드체**
__볼드체**
```
     - 결과 :   
**볼드체**  
__볼드체__
  - **이탤릭 (Italic)**
```
*이탤릭*
_이탤릭_
```
    - 결과  
*이탤릭*
_이탤릭_
  - **취소선**
```
  ~~취소선~~
```
    - 결과  
    ~~취소선~~  
  - **볼드, 이탤릭 혼합 사용**  
```
**볼드와 _이탤릭_ 혼합사용**
```
    - 결과  
    **볼드와 _이탤릭_ 혼합사용**  

#### 인용
  - **문법**
```
>인용
>>인용
>>>인용
```
    - 결과  
    >인용
    >>인용
    >>>인용

#### 코드 블록(Code Block)
  - **문법**  
~~~
```
  코드 블록
```
~~~
    - 결과  
```
코드블록
```  

  - **코드 블록 강조**
  ~~~
  ```ruby
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  ```
  ~~~
    - 결과  
    ```ruby
    require 'redcarpet'
    markdown = Redcarpet.new("Hello World!")
    puts markdown.to_html
    ```


#### 링크(Link)
  - **링크**
```
[Link](https://www.stardocksystems.com/markdown/2015/04/18/StartMarkDown.html)
```
    - 결과  
      [Link](https://www.stardocksystems.com/markdown/2015/04/18/StartMarkDown.html)  

  - **섹션 링크**
```
<a name="Section">
  Text
</a>  
  [Section Link](#Section_1)
```
    - 결과  
      [Section Link](#Section_1)  

  - 관련 링크

#### 목록 (List)
  * 기호 목록
  * 숫자 목록
  * 중첩 목록
  * 작업 목록
