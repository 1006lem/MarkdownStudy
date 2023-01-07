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
---
## 문법
### 목차
[1. 제목(Header)](1.제목-Header)<br>
[2. 강조(Enphasis)](2.강조-Emphasis)<br>
[3. 인용(Block-quotes)](3.인용-Block-Quotes)<br>
[4. 코드 블럭(Code Block)](4.코드블럭-CodeBlock)<br>
[5. 리스트(List))](5.리스트-List)<br>
[6. 링크(Link))](6.링크-Link)<br>
[7. 이미지(Image)](7.이미지-Image)<br>
[8. 표(Table)](8.표-Table)<br>
[9. 이모티콘](9.이모티콘)<br>

### 1. 제목(Header)
### 2. 강조(Enphasis)
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

### 3. 인용(Block-quotes)
~~~
>
>>
>>>
~~~
### 4. 코드 블럭(Code Block)

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
    
    
### 5. 리스트(List)
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
 
### 6. 링크(Link)
#### 내부 링크
~~~
[1. 제목(Header)](1.제목-Header)<br>
~~~
[1. 제목(Header)](1.제목-Header)<br>
#### 외부 링크

### 7. 이미지(Image)
- 비율로 지정 가능(width = "30%")
~~~
<img width="300" src="(이미지경로).png">
~~~
<img width="300" src="https://user-images.githubusercontent.com/68532437/211111919-861dab9f-5764-4f08-8057-83683e4f682a.png">

### 8. 표(Table)
### 9. 이모티콘
~~~
:sparkles:
~~~
:sparkles:

- <a href="https://www.webfx.com/tools/emoji-cheat-sheet/">Emoji Cheat Sheet</a>

### ~~10. 각주(Footnotes)~~ github에서는 지원 x
~~~
computer networking system[^1]
[^1]: a definition, ...
~~~

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

<span style="color:red">red</span>
<p style='color:red>red</p><br>
<font color='red'>red</font><br>
<b stype='color:red'>red</b><br>
~~~
$$\textcolor{yellow}{\text{Hello }}{\text{Welcome}}\textcolor{yellow}{\text{ my page}}$$
$\textcolor{green}{\text{Hello, }}$ Welcome!

~~<span style="color:red">red</span>~~
~~<p style='color:red>red</p><br>~~
~~<font color='red'>red</font><br>~~
~~<b stype='color:red'>red</b><br>~~
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

 ### 13. 체크박스
 ~~~
 - [] check1
 - [] check2
 ~~~
- [] check1
- [] check2


