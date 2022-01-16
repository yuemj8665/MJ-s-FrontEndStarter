
3. border
    - 테두리의 두께, 종류, 색상을 결정.
    - 요소의 테두리 선을 지정하는 단축 속성
    - 요소의 크기가 커진다.
    - 선-두께 선-종류 선-색상;
    - border-width border-style border-color;
* border-width
    - medium : 기본값, 중간두께, 그러나 브라우저마다 기준이 다르기때문에 되도록 피하는게 좋다.
    - thin
    - thick
    - 단위 : px, em, % 등, 단위로 지정
    - border-width는 뒤에 붙는 숫자의 수 만큼 상단, 우측, 하단, 좌측의 수치를 결정한다.
    
    ![border-width](https://blogfiles.pstatic.net/MjAyMjAxMDVfNDkg/MDAxNjQxMzA5MzQ1NzYx.JHujJ3VziWSPk9nclX6CTbx46xpei7GDu9LhMfebrnMg.5Lj4mAV_E182mKypNplDgYVkIiR9DS24E6B-5M5lsu8g.PNG.yuemj/width.png?type=w1)
* border-stlye
    - 요소 테두리 선의 종류
    - *none : 기본값, 선 없음*
    - *solid : 실선(일반 선)*
    - dotted : 점선
    - *dashed : 파선*
    - double : 두 줄 선
    - groove : 홈이 파여있는 모양
    - ridge : 솟은 모양 (groove와 반대)
    - inset : 요소 전체가 들어간 모양
    - outset : 요소 전체가 나온 모양
    - border-stlye 뒤에 붙는 숫자의 속성만큼 각 선의 모양을 지정 할 수 있다.

    ![border-stlye](https://blogfiles.pstatic.net/MjAyMjAxMDVfNzcg/MDAxNjQxMzA5MzQxMjQw.zV1tTE26Bg564xVLGXCn8GS16xN3MBDC0XQcbFtLk90g.PSSW-cr4kdJXVgZvQo_cpOrxccHqQxNT3_5Vs7HQmLwg.PNG.yuemj/style.png?type=w1)
* border-color 
    - 요소 테두리 선의 색상을 지정하는 단축 속성
    - black : 기본값, 검정색
    - 색상 : 선의 색상
    - transparent : 투명
    - border-color 뒤에 붙는 숫자의 속성만큼 각 선의 색상을 지정 할 수 있다.
    - 색상 표현
        - 색상 이름 : 브라우저에서 제공하는 색상 표현 (red, tomato, royalblue 등...)
        - Hex 색상코드 : 16진수 색상 (#000, #FFFFFF 등..)
        - RGB : 빛의 삼원색 (RGB(255, 255, 255))
        - RGBA : 빛의 삼원색 + 투명도 (RGBA(0, 0, 0, 0.5))

    ![border-color ](https://blogfiles.pstatic.net/MjAyMjAxMDVfMTQz/MDAxNjQxMzA5MzUwNTY3.I4UADxJJ6vB1pWtXjGunjxPOFpVIVOUK0HvwBrj1KSEg.z91CnmRaiDpyMNEfs_WeGuLrTArMcz0ZzhDIXWkKUQMg.JPEG.yuemj/%EC%83%89%EC%83%81%ED%91%9C%ED%98%84.jpg?type=w1)

    ![border-color ](https://blogfiles.pstatic.net/MjAyMjAxMDVfMjI1/MDAxNjQxMzA5MzM2ODY5.fBfUXydDry2Xdlh_WTmZl5bF8YxiCyZmKkm-l2v4b5Ag.J7mh5iBDcEOhNHmH0K0mFuDHX3pL9BL-wFJNex2n88wg.PNG.yuemj/color.png?type=w1)
* border-방향, border-방향-속성
    - 요소의 테두리 선을 지정하는 기타 속성들
    - border-top-width : 위쪽 선의 두께
    - border-left-stlye : 왼쪽 선의 종류
    - border-right-color : 오른쪽 선의 색상 등...
    
* border-radius
    - 0 : 기본값, 둥글게 없음
    - 단위 : px,me,vm 등 단위로 지정.
    - border-radius 뒤에 붙는 숫자의 속성만큼 각 모서리의 둥근 정도를 결정 할 수 있다.

    ![borderRadius](https://blogfiles.pstatic.net/MjAyMjAxMDVfOTgg/MDAxNjQxMzkxNjAyOTY4.WLGitbcytfWkHh17LLunoabMnDpWoMhAAiR3hRzjKhQg.JxTwMYRhUqJPuWc4ZWWyu55P1Egn_POaSDZAfA4X778g.JPEG.yuemj/2022-01-05_radius.jpg?type=w1)

* 정리
    - border 속성의 특징 : padding과 동일하게 요소의 크기가 늘어난다.

    ![borderResult](https://blogfiles.pstatic.net/MjAyMjAxMDVfMjgy/MDAxNjQxMzA5MzI1NzY2.S9daliseBd-G8DpOP0nfLXAIbX0iYSJkBR_XkP0av1wg.yVKl1C0fDWtlh0uJ3On9M2_jQQNJENrZ_GUhqdAdSRkg.PNG.yuemj/PRACTICE.png?type=w1)
