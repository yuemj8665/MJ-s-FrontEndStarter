
## 7.2. 글꼴, 문자
- 폰트, 서체.
- 글꼴의 크기나 두께 제어.
  
### 7.2.1 font-style
- 글자의 기울기
- nomal : 기본값, 기울기 없음
- titalic : 이텔릭체
- oblique : 기울어진 글자

### 7.2.2. font-weight
- nomal, 400 : 기본값, 기본 두께
- bold, 700 : 두껍게
- bolder : 상위(부모) 요소보다 더 두껍게
- lighter : 상위(부모) 요소보다 더 얇기
- 100 ~ 900 : 100단위의 숫자 9단계의 숫자

### 7.2.3. font-size
- 16px : 기본값, 기본 두꼐
- 단위 : px, em, rem 등, 단위로 지정
- % : 부모 요소의 폰트 크기에 대한 비율
- smaller : 상위(부모) 요소보다 더 작게
- larger : 상위(부모) 요소보다 더 크게
- xx-small ~ xx-large : 가장 작게~가장 크게.

### 7.2.4. link-height
- 한 줄의 높이, 행간과 유사하다
- nomal : 브라우저의 기본 정의를 사용.
- 숫자 : 요소의 글꼴의 크기의 배수로 지정.
- 단위 : px,em,rem등의 단위로 지정
- % : 요소의 글꼴 크기의 비율로 지정

![font1](https://blogfiles.pstatic.net/MjAyMjAxMDlfMTYx/MDAxNjQxNzM0MTYyNzIz.obnhNrio4vPG0o0TGOUzt7VlyX6pmJFLpnLcoT5Kxg4g.FVsrONdLd3qNQWqiVp18sury847lL_BsBEtJZTowDf0g.JPEG.yuemj/2022-01-09_font1.jpg?type=w1)


### 7.2.5. font-family
- 글꼴(서체) 지정
- 글꼴, "글꼴2", ... 글꼴 계열(serif)
- 글꼴 계열 : 필수로 작성.
    - serif : 바탕체 계열
    - sans-serif : 고딕체 계열
    - monospace : 고정너비(가로폭이 동등) 글꼴 계열
    - cursive : 필기체
    - fantasy : 장식 글꼴 계열
- 띄어쓰기 등, 특수문자가 포함된 글꼴 이름은 큰 따옴표로 묶어야 한다.
- 글꼴의 후보 지정하는 이유는 브라우저가 사용 할 수 있는 글꼴들의 우선순위로 시도한다.
- 글꼴 후보들을 전부 사용 할 수 없는 상황이라면, 마지막의 작성 된 필수값인 글꼴 계열을 사용한다.

![font2](https://blogfiles.pstatic.net/MjAyMjAxMDlfNDEg/MDAxNjQxNzM0MTcwMzU2.Q8XIaMKXlV8VLd97HNYW0buyR8w45yrdRJ24Cdbz71kg.XvINgS50ZuLt8NsCYz7RUdIwfyopH1o42ePtlwitwTYg.JPEG.yuemj/2022-01-09_font3.jpg?type=w1)


