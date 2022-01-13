## 1.8.15. position
- 요소의 위치 지정 기준
- static : 기본값, 기준 없음
  
![position_nomal](https://blogfiles.pstatic.net/MjAyMjAxMTNfMTUz/MDAxNjQyMDg1MzgwODY2.SHLQCCSZAZd7L5HZy0APnBhTdWlV0c6-3tvD5MZNuMMg.aSaf0fYlHMeo1ez2AKArZuhhNnWoYuq10xuuHsUSv4Ig.JPEG.yuemj/position_nomal.jpg?type=w1)
- relative : 요소 자신을 기준으로
- absolute : 위치 상 부모 요소를 기준으로
    - 위치 상 부모 요소를 꼭 확인해야 한다.

![position_absoute1](https://blogfiles.pstatic.net/MjAyMjAxMTNfMTkx/MDAxNjQyMDg1MzgxMjY2.XQLOyrQXl734Xf2peuu57JQVZOEYPinrmJOXZhTMlysg.7bXoVe7Ue0O8KvEWvgs9G8UQEqUvRwxMJ86duJfIRA4g.JPEG.yuemj/position_absolute.jpg?type=w1)
![position_absoute2](https://blogfiles.pstatic.net/MjAyMjAxMTNfODgg/MDAxNjQyMDg1MzgxNTc0.p3mAAFH5I-FJ9yakYONs9VDJkUqywduAc_vKSIx9DAog.rtoFd7BBBfCJinRHXCLSlffww5P5q29OKwVBfQZL-PYg.JPEG.yuemj/position_absolute2.jpg?type=w1)
![position_absoute3](https://blogfiles.pstatic.net/MjAyMjAxMTNfMjY5/MDAxNjQyMDg1MzgxOTA3.IJy7R1GT9HHH4su_W41bM_WSE4-N6jljKu3uqKto_esg.dzd-8n0XhckrYYbDwOshQ25deCuKhNHo10VYkduxViYg.JPEG.yuemj/position_absolute3.jpg?type=w1)
        
- fixed : 뷰포트(브라우저)를 기준으로

![position_fixed](https://blogfiles.pstatic.net/MjAyMjAxMTNfMTg2/MDAxNjQyMDgzNjkzOTE1.XUUyeiwnxbkCfEFe4Tq4PlL7iIQ1frTQ2lAwBM0Vihkg.uJK1B6lEOD4016t12f0G5Qw10x1jTZj7FxjasUvlpuYg.GIF.yuemj/position_fixed.gif?type=w1)  

- position과 같이 사용할 수 있는 CSS 속성
    - 요소의 각 방향별 거리 지정
        - auto : 브라우저가 계산해서 넣는다.
        - 아래 속성들은 음수값을 지정 가능하다.
        - top 
        - bottom
        - left
        - right
        - z-index : 쌓는 순서를 정한다.
    
- 요소 쌓임 순서(Stack order)
    - 어떤 요소가 사용자와 더 가깝게 있는지(위에 쌓여있는지) 결정한다
    1. 요소에 position 속성의 값이 있는 경우, 위에 쌓인다(기본값 static 제외)
    2. 1번 조건이 같은 경우, z-index 속성의 숫자 값이 높을 수록 위에 쌓인다.
    3. 1번과 2번의 조건까지 같은 경우, HTML의 다음 구조일수록 위에 쌓인다.
    
![position_Stack_order](https://blogfiles.pstatic.net/MjAyMjAxMTNfMzAw/MDAxNjQyMDg1MzgyMzAy.MKmVV63QU4ubhBxMvum7u4wwoinD9s3kh0CPfONY2dEg.zilODG_eHYaA5SU5fSxEs1OnMnmzPLILhxMC9aFNK2Eg.JPEG.yuemj/position_z-index.jpg?type=w1)