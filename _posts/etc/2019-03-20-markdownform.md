---
layout: post
title: 'MARKDOWN 사용법(문법)'
excerpt: 제목, 인용문, 목록(글번호 유무), 코드, 수평선, 링크, 강조, 이미지
category: etc
tags:
  - MARKDOWN
  - 마크다운
  - 마크다운 문법
comments: false
---

# Header

* 큰 제목 : 문서제목

        큰 제목
        ===

  큰 제목
  ===

* 작은 제목 : 문서 부제목
  
        문서 부제목
        ---

  문서 부제목
  ---  

* 글머리 : 1~6까지 지원
  
        # h1
        ## h2
        ### h3
        #### h4
        ##### h5
        ###### h6

  # h1
  ## h2
  ### h3
  #### h4
  ##### h5
  ###### h6


# BlockQuote
    '>'를 블럭 인용문자로 사용
    > 1개 사용한 블럭인용
    >> 2개 사용한 블럭인용
    >>> 3개 사용한 블럭인용
    >>>> 4개 사용한 블럭인용
    >>>>> 5개 사용한 블럭인용.....

'>'를 블럭 인용문자로 사용
> 1개 사용한 블럭인용
>> 2개 사용한 블럭인용
>>> 3개 사용한 블럭인용
>>>> 4개 사용한 블럭인용
>>>>> 5개 사용한 블럭인용.....

이 안에 다른 마크다운요소 사용 가능함.

    >한번 사용함
    > 
    > * 마크다운 표기 가능
    > 
    >       코드

>한번 사용함
> 
> * 마크다운 표기 가능
> 
>       코드

# 목록

## 1. 순서가 있는 목록(번호)

    1. 첫번째
    2. 두번째
    3. 세번째

    4. 3번째
    5. 1번째
    6. 2번째


1. 첫번째
2. 두번째
3. 세번째
   
4. 3번째
5. 1번째
6. 2번째

-> 앞에서 라벨링한 숫자와 상관없이 내림차순으로 번호 매겨짐

## 2. 순서없는 목록(글번호 기호)

>'*', '+', '-' 모두 동일함
>(이들을 혼합하여 사용하여도 결과 동일함)

      * 첫번째
        * 두번째
          * 세번째
            * 네번째
              * 다섯번째
  
* 첫번째
  * 두번째
    * 세번째
      * 네번째
        * 다섯번째



# 코드 

> 4개의 공백 또는 1개의 tab으로 들여쓰기 시작하여, 들여쓰기 안되있는 곳까지 적용됨

    public class HelloWorld{
        public static void main(String[] args){
            System.out.println("Hello, world!")
        }
    }


# 수평선

>마크다운 문서 미리보기로 출력하거나 페이지 나누는 용도로 사용
(모두 동일한 결과)

    ***
    *   *   *
    *******
    -   -  -   
    --------------

***
*   *   *
*******
-   -  -   
--------------

# 링크
* 참조링크

        [link keyword][id]
        [id]:URL "Optional Title here"

        Link:[Google][googlelink]
        [googlelink]: https//google.com "Go google"

[Google][googlelink] 
[googlelink]:https://google.com "Go google"

* 인라인 링크
 
        syntax:[title](link)
        [title](link)
        ex) syntax:[google](https//google.com)

    syntax:[google](https//google.com)

    [google](https//google.com)

* 자동연결

        <http://example.com/>
        <address@example.com>

  <http://example.com/>
  <address@example.com>

# 강조

    *single asterisks* 이텔릭체
    _single underscores_ 이텔릭체
    **double asterisks** 볼드체
    __double underscores__ 볼드체
    ++underline++  밑줄
    ~~cancelline~~ 삭제 줄

*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~

# 표 작성
> 표 만들어주는 사이트 참고
> [관련 사이트](http://www.tablesgenerator.com/markdown_tables)


# 이미지
    ![대체택스트](파일경로)
    ![대체택스트](/img/sample/sampleImg.jpg)
    ![대체텍스트](/img/sample/sampleImg.jpg "Optional title")

![Alt text](/img/sample/sampleImg.jpg)
![Alt text](/img/sample/sampleImg.jpg "Optional title")

# 기타 문법 사항
> [관련 사이트1](https://blog.kalkin7.com/2014/02/05/wordpress-markdown-quick-reference-for-koreans/)
> [관련 사이트2](https://blog.kalkin7.com/2014/02/05/wordpress-markdown-quick-reference-for-koreans/)
> [관련 사이트3](http://magic.wickedmiso.com/117)

* 참고문서
  > ihoneymon의 마크다운 markdown 작성법 [관련문서링크](https://gist.github.com/ihoneymon/652be052a0727ad59601)
  >
  > 놀부의 마크다운 사용법 
    [관련문서링크](https://nolboo.kim/blog/2014/04/15/how-to-use-markdown/)
  >
  > 허니몬의 마크다운 Markdown 이야기
  [관련문서링크](https://www.slideshare.net/ihoneymon/ss-40575068)
  >
  > https://hashcode.co.kr/questions/1772/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%AC%B8%EB%B2%95-%EC%9E%91%EC%84%B1-%ED%8C%81
  >
  >https://blog.kalkin7.com/2014/02/05/wordpress-markdown-quick-reference-for-koreans/
  >
  >https://blog.kalkin7.com/2014/02/05/wordpress-markdown-quick-reference-for-koreans/
  >
  >http://magic.wickedmiso.com/117

 



