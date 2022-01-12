
## 1.8.14. 배경
- 요소의 배경 색상이나 이미지 삽입으로 제어 가능
* background-color
    - 요소의 배경 색상
    - transparent : 기본값, 투명함
    - 색상 : 지정 가능한 색상
* background-image
    - 요소의 배경 이미지 삽입
    - none : 기본값, 이미지 없음
    - url("경로") : 이미지 경로
    * background-repeat
        - 요소의 배경 이미지 반복
        - repeat : 기본값, 이미지를 수직, 수평반복
        - repeat-x : 이미지를 수평 반복
        - repeat-y : 이미지를 수직 반복
        - none-repeat : 반복 없음

* background-position
    - 요소의 배경 이미지 위치
    - 0%~100% : x축,y축, 위에서 아래로, 0%~100% 사이 값
    - 방향 : top, bottom, left, right, center 방향
    - 단위 : px,em,rem 등 단위로 지정

* background-size
    - auto : 기본값, 이미지의 실제 크기
    - 단위 : px,em,rem 등 단위로 지정
    - cover : 비율을 유지, 요소의 더 넓은 너비에 맞춤
    - contain : 비율을 유지 요소의 더 짧은 너비에 맞춤

* background-attachment (페럴렉스)
    - 요소의 배경 이미지 스크롤 특성
    - scroll : 기본값, 이미지가 요소를 따라서 **같이 스크롤**
    - fixed : 이미지가 뷰포트에 고정, **스크롤 X**
    - local : 요소 내 스크롤 시 이미지가 같이 스크롤
