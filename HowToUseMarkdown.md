# Markdown 내용 정리

---

## 마크다운(Markdown) 이란?
- `test to HTML` 컨버팅 도구

### :star2: 장단점

| 장/단점|  |
| ---- | ------------------------------------------- |
| 장점 | - 문법이 간결하고 쉽다  |
|      | - `HTML`로 변환 가능하다  |
|      | - `.txt`파일로, 별도의 도구 없이 작성 가능하다  |
| 단점 | - 표준이 없다  |
|      | - HTML 마크업 전부를 대신하지는 못한다  |

:books: 참고 자료
  - <a href="https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax">Github 공식문서</a> ⭐
  -  <a href="https://blog.potados.com/dev/github-readme-zen/">마크다운에 생기를 </a>
  - <a href="https://gist.github.com/ihoneymon/652be052a0727ad59601">[공통]마크다운 markdown 작성법</a>
  - <a href="https://www.markdownguide.org/getting-started/">markdown guide</a>
  - <a href="https://goddaehee.tistory.com/307">마크다운(MarkDown) 사용법</a>
  - <a href="https://heropy.blog/2017/09/30/markdown/ MarkDown">MarkDown 사용법 총정리</a>
  - <a href="https://wwlee94.github.io/category/blog/getting-started-markdown/">마크다운 (Markdown) 문법 알아보기</a>  
  - <a href="https://80000coding.oopy.io/bbfbfed5-d55c-4aaf-a2b8-b52578472d0d">마크다운 초보가 쓰는 마크다운 고수되는 법</a>        
  - <a href="https://github.com/yona-projects/yona/issues/474  ">마크다운 color text</a>     
  - <a href="https://jihyehwang09.github.io/2020/03/04/markdown-how-to-make-link/">목차쓰기</a>
---
## 문법
<!--
### 🌟 목차

[1. 제목(Header)](#1.-제목-(header))<br>
[2. 강조(Enphasis)](###2.강조-(Emphasis))<br>
[3. 인용(Block-quotes)](#3.인용-Block-Quotes)<br>
[4. 코드 블럭(Code Block)](#4.코드블럭-CodeBlock)<br>
[5. 리스트(List))](#5.리스트-List)<br>
[6. 링크(Link))](#6.링크-Link)<br>
[7. 이미지(Image)](#7.이미지-Image)<br>
[8. 표(Table)](#8.표-Table)<br>
[9. 이모티콘](#9.이모티콘)<br>
-->
---
### 0. 공백(blank)
- https://kimasill.tistory.com/entry/MarkDown-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%9D%84%EC%96%B4%EC%93%B0%EA%B8%B0%EA%B3%B5%EB%B0%B1-%EC%A4%84%EB%B0%94%EA%BF%88-%EC%82%AC%EC%9A%A9%EB%B2%95
- 1. 특수 코드 `&nbsp;` 사용
- 2. 전각 공백 사용: :star2:  :star2: 


### 1. 링크(Link)
#### 내부 링크
- 문자의 공백은 `-` 로 
- 영어는 소문자로
- 특수 문자(`.`, `?`, ''...) 는 작성 x
- 내부의 괄호는 작성 x

~~~
[1. 제목(Header)](#1-제목-header)<br>
~~~
[1. 제목(Header)](#1-제목-header)<br>


#### 외부 링크
~~~
*더 자세한 내용은 다음 링크의 **[2.4 할당 방법](https://github.com/boanlab/study-notes/blob/main/major_subjects/operating_system/06_fileSystem/README.md)** 을 참고하자*
~~~
*더 자세한 내용은 다음 링크의 **[2.4 할당 방법](https://github.com/boanlab/study-notes/blob/main/major_subjects/operating_system/06_fileSystem/README.md)** 을 참고하자*

### 2. 이미지(Image)
- 비율로 지정 가능(width = "30%")
~~~
<img width="300" src="(이미지경로).png">
~~~
<img width="300" src="https://user-images.githubusercontent.com/68532437/211111919-861dab9f-5764-4f08-8057-83683e4f682a.png">

- 이미지 클릭 시 원본 링크로 연결되는 
~~~
[![텍스트](이미지 파일 경로)](연결되고 싶은 링크 주소)
~~~
```
[![inodeDataBlock구조](https://oopy.lazyrockets.com/api/v2/notion/image?src=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fe5485c09-fe76-4d1f-a007-550ce005c1c2%2FUntitled.png&blockId=05be8ef1-f3d0-4b29-8a4b-e8b18f2de89f)](https://driip.me/dbd9bc58-0ce1-437b-af4f-7b2bde2b1bf3)
```
[![inodeDataBlock구조](https://oopy.lazyrockets.com/api/v2/notion/image?src=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fe5485c09-fe76-4d1f-a007-550ce005c1c2%2FUntitled.png&blockId=05be8ef1-f3d0-4b29-8a4b-e8b18f2de89f)](https://driip.me/dbd9bc58-0ce1-437b-af4f-7b2bde2b1bf3)

:warning: 궁금한 점: 이렇게 이미지 클릭 시 원본 링크로 연결되도록 하면, 이미지의 크기는 수정할 수 없나?




### 3. 제목(Header)
### 4. 강조(Enphasis)
#### - 버튼 강조
~~~
<kbd>ESC</kbd>를 누르세요
~~~
<kbd>ESC</kbd>를 누르세요

#### - 글씨 강조
~~~
*itaic*
_italic_
**bold**
__bold__
~~del~~
__italic__ and **bold**
<ins>interesting</ins><br>
~~~

*itaic*<br>
_italic_<br>
**bold**<br>
__bold__<br>
~~del~~<br>
__italic__ and **bold**<br>
<ins>interesting</ins><br>


#### - 기타
~~~
> __Warning__
> warning !

> __Note__
> inform
~~~
> __Warning__
> warning !

> __Note__
> inform

### 5. 인용(Block-quotes)
~~~
>
>>
>>>
~~~
### 6. 코드 블럭(Code Block)

    ```c
    //Code Block for c
    void main(){
        printf("Hello");
        return 0;
    }
    ```
```c
//Code Block for c
void main(){
    printf("Hello");
    return 0;
}
 ```    
    ~~~
    you can just use Tilede(~)
    ~~~
~~~
you can just use Tilede(~)
~~~
    
    
### 7. 리스트(List)
~~~
* 오늘의 점심
  - 돈까스
  + 우동
  * 샐러드
~~~
* 오늘의 점심
  - 돈까스
  + 우동
  * 샐러드
 

### 8. 표(Table)

### 9. 이모티콘
~~~
:sparkles:
~~~
:sparkles:

- <a href="https://www.webfx.com/tools/emoji-cheat-sheet/">Emoji Cheat Sheet</a>

### 10. 각주(Footnotes)
#1.
~~~
# 1. 이 방식은 github에서 사용할 수 **없다**
computer networking system[^1]
[^1]: a definition, ...
~~~
#2.  
~~~
# 2. 
설명🔗<sup id="a3">[1](#f3)</sup>

<b id="f3"> 설명(spool)</b><br>
  설명
  [↩](#a3)
  
~~~
설명🔗<sup id="a3">[1](#f3)</sup>

<b id="f3"> 설명(spool)</b><br>
  설명
  [↩](#a3)
  
### 11. 접기/펼치기
~~~
<details>
<summary>click me</summmary>

반갑습니다:star2:
</details>
~~~

<details>
<summary>click me</summary>

반갑습니다:star2:
</details>

### 12. 색(color)
~~~
$$\textcolor{yellow}{\text{Hello }}{\text{Welcome}}\textcolor{yellow}{\text{ my page}}$$
$\textcolor{green}{\text{Hello, }}$ Welcome!
~~~
$$\textcolor{yellow}{\text{Hello }}{\text{Welcome}}\textcolor{yellow}{\text{ my page}}$$
$\textcolor{green}{\text{Hello, }}$ Welcome!

<!--
~~<span style="color:red">red</span>~~
~~<p style='color:red>red</p><br>~~
~~<font color='red'>red</font><br>~~
~~<b stype='color:red'>red</b><br>~~
-->
~~~
```diff
- red
+ green
! orange
# gray
@@ purple + bold @@
```
~~~
```diff
- red
+ green
! orange
# gray
@@ purple + bold @@
```

 
 <!-- ### 13. 체크박스
 - [] check1
 - [] check2
 ~~~
- [] check1
- [] check2
-->

