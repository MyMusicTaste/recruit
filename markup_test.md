# Markup Test
* **데모영상과 얼마나 똑같이 만드느냐보다는 요구사항과 주어진 디자인을 이해하고 개발할 수 있는 능력을 보는 과제입니다.** 
* [에셋 다운로드](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/markup_test_assets.zip) / [데모영상](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/test-example.mov)
* 아래 명시된 스펙을 최대한 반영한 산출물을 완성하여 보내주세요.
* 산출물에는 html, img, css(sass), js 파일 모두 있어야 합니다.
* 스타일 작업은 sass(scss)로 작업 후 css로 컴파일 해주세요.
<br>

## 주요 평가항목
* 디자인 시안을 보고 구체적인 가이드 없이도 구조를 짤 수 있는가?
* sass(scss)를 사용할 수 있는가?
* 반응협 웹을 구현할 수 있는가? 미디어쿼리를 사용할 수 있는가?
* 웹 폰트를 사용할 수 있는가?
* jQuery plugin을 사용할 수 있는가?
* 간단한 javascript(jQuery)를 짤 수 있는가?
* 요구사항을 정확히 이해할 수 있는가?
<br>

## Wording
```
CONGRATULATIONS, YOU’VE SOLVED THE PUZZLE!
STAY TUNED FOR SOMETHING AMAZING
```
```
JOIN MyMusicTaste
for THE EXPERIENCE of a LIFETIME

Congratulations, you’ve solved the puzzle!
You are one step closer to finding out which KPOP boy band will be taking North America by storm with MyMusicTaste.

The group we will bring is one of the six shown below. Time is running out so click on the photo of your favorite group to MAKE your concert today! Who knows...we may be bringing them to a city near you...

#StopWishingStartMaking with MyMusicTaste!
```
<br>

## Style Guide
* **[size]** Web(width: 1280 ~ 1920px) / Mobile(width: 375 ~ 425px)를 기준으로 반응형 웹페이지를 만든다.
  * width: 426~1179px 범위는 필수는 아니지만 이 부분까지 고려된 반응형 웹일 경우 가산점 있음
* **[hover]** 모든 버튼들의 hover style은 default(opacity 0.8) -> hover(opacity: 1.0) 이다. 
* **[font]** Lato, Roboto Condensed를 활용한다. 스크린샷을 참고하여 적절한 font-size, line-height, letter-spacing을 사용한다.
* **[color]** 모든 폰트는 #ffffff 색을 사용한다.
<br>

## Web Spec
* 총 3개의 섹션으로 구성되어 있다. (메인 / 소개 / 슬라이더)
* 한 섹션은 윈도우 창이 꽉 찬 풀 페이지[(예시)](https://alvarotrigo.com/fullPage/)로 구성된다.
* sticky menu(SHARE ON [facebook icon] [tweeter icon])이 왼쪽 사이드 중앙에 항상 따라다닌다.
<br>

### 1. 메인
* 배경에 0~9의 숫자와 공백이 랜덤으로 출력되어 깜빡거리는 느낌을 구현한다.
* 가운데에 `vid01.mp4` 영상이 무한으로 자동 재생된다.<br> 
![test-pc1](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/test-pc1.png)
<br>

### 2. 소개
* 오른쪽 하단 기준으로 배경 이미지가 깔려있다.
* 주어진 워딩을 적절히 배치한다.<br> 
![test-pc2](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/test-pc2.png)
<br>

### 3. 슬라이더
* **[데모영상](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/test-example.mov) 확인 필요**<br>
* 3개의 슬라이더가 동시에 넘어가지 않고 시간차를 조금씩 주면서 랜덤하게 넘어가도록 한다.
* 하단에 SNS 로고 4개가 있다.
![test-pc3](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/test-pc3.png)
<br>

## Mobile Spec
* 웹 페이지에서 영상이었던 부분이 `bg_intro_m.gif`로 변경된다.
* 웹 페이지에서 슬라이더 였던 부분이 리스트형으로 변경된다.
* 웹 페이지에서 있던 sticky menu가 사라진다.<br> 
![test-mobile](http://production.media.mymusictaste.com.s3.amazonaws.com/static/img/temp/test-mobile.png)
