# 7. 속성
- 우리가 소스를 적용하면서 어떻게 생성이 될지 상상하는게 필요하다.

## 7.1. 박스모델
- HTML요소의 박스를 정의한다.
- 기본적으로 사각형

### 7.1.1. 요소의 가로/세로 너비
1.  width/height
    - 가로, 세로너비를 지정한다.
    - 단위 : px, em, vs 등 단위로 지정
    - auto : 기본값, 브라우저가 너비를 계산
    - span은 대표적인 인라인 요소.
        - 본질적으로 아무것도 나타내지 않는, 콘텐츠의 영역을 설정하는 용도.
        - **포함한 콘텐츠 크기만큼 자동으로 줄어든다.**
        - 가로너비와 세로너비를 지정 할 수 없다.
        - 글자를 적용시키기 위한 것
    - div는 대표적인 블록라인 요소.
        - **가로 너비는 부모 요소의 크기만큼 자동으로 늘어난다**
        - **세로 너비는 콘텐츠 크기만큼 자동으로 줄어들게 된다.**

2. max-width / max-height
    - 요소가 커질 수 있는 최대 가로/세로 너비
    - none : 기본값, 최대 너비 제한 없음
    - auto : 브라우저가 너비를 계산한다
    - 단위 : px, em, vs등 단위로 지정

3. min-width / min-height
    - 요소가 작아질 수 있는 최소 가로/세로 너비
    - 0 : 기본 값, 최소 너비 제한 없음
    - auto : 브라우저가 너비를 계산한다
    - 단위 : px, em, vs등 단위로 지정


4. 정리
    - width, height 속성의 역할은 가로, 세로너비를 지정한다.
    - width, height 속성의 기본값은 auto.
    - max-width / max-height 속성의 기본값은 none;
    - min-width / min-height 속성의 기본값은 0;
