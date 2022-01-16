## 1.8.15. position-2
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