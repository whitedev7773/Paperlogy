# Paperlogy
> G마켓산스의 한글과 Montserrat의 영문을 결합한 폰트에요. 한글 2,780자만 사용하여 파일 크기를 줄였어요. (원본 파일 평균 : 약 646KB / 웹폰트 평균 : 421KB) https://freesentation.blog/paperlogyfont

페이퍼로지 폰트를 웹에서 사용할 수 있게 변환한 웹폰트입니다.
페이퍼로지 웹폰트

## 🧑‍💻 폰트 개발자

[![폰트 소개 영상](http://img.youtube.com/vi/CWcclSEbOJk/maxresdefault.jpg)](https://youtu.be/CWcclSEbOJk)

<br/>

[![paperlopy](https://img.shields.io/badge/paperlogy-white?style=for-the-badge&logo=youtube&logoColor=ff0000&label=youtube&labelColor=white&color=ff0000)](https://www.youtube.com/@paperlogy)
[![ptkkun](https://img.shields.io/badge/PTKkun-white?style=for-the-badge&logo=youtube&logoColor=ff0000&label=youtube&labelColor=white&color=ff0000)](https://www.youtube.com/@PTKKUN_PPT)


페이퍼로지 폰트는 `PPT 유튜버 페이퍼로지`님과 Freesentation 폰트를 개발한 `이주임 프레젠테이션 디자이너`님의 공동으로 개발한 폰트입니다.

## 🔍 미리보기
[Playground](https://htmlpreview.github.io/?https://github.com/whitedev7773/Paperlogy/blob/master/index.html)

[![폰트 미리보기](https://raw.githubusercontent.com/whitedev7773/Paperlogy/main/demo.png)](https://htmlpreview.github.io/?https://github.com/whitedev7773/Paperlogy/blob/master/index.html)

## 🪚 폰트 굵기
페이퍼로지 폰트는 총 9가지의 굵기를 지원합니다.  
CSS의 `font-weight: 100`~`900`을 모두 사용할 수 있습니다.
| Weight Name | CSS Value | 설명          |
| :---        | :---      | ---:          |
| Thin        | 100       | 가장 얇음     |
| ExtraLight  | 200       |               |
| Light       | 300       |               |
| Regular     | 400       | 일반적인 두께 |
| Medium      | 500       |               |
| SemiBold    | 600       |               |
| Bold        | 700       |               |
| ExtraBold   | 800       |               |
| Black       | 900       | 가장 두꺼움   |

## ✏️ 사용 방법
### `<link>` 방식
> HTML 문서에 아래 link 태그를 추가하여 폰트를 불러올 수 있어요.  
> @import 방식 대신 쓰는 걸 추천해요.
> ```html
> <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/whitedev7773/Paperlogy/paperlogy.css">
> ```
### `@import` 방식
> css 파일에서 @import를 추가해서 폰트를 불러올 수 있어요.  
> 이 방식 대신 link 방식을 쓰는 걸 추천해요.
> ```css
> @import url(https://cdn.jsdelivr.net/gh/whitedev7773/Paperlogy/paperlogy.css);
> ```

## ✅ 적용
> css 적용 예시
> ```css
> body			{ font-family: 'Paperlogy', sans-serif }
> .thin			{ font-weight: 100 }
> .light			{ font-weight: 200 }
> .extralight		{ font-weight: 300 }
> .regular		{ font-weight: 400 }
> .medium			{ font-weight: 500 }
> .semibold		{ font-weight: 600 }
> .bold			{ font-weight: 700 }
> .extrabold		{ font-weight: 800 }
> .black			{ font-weight: 900 }
> ```