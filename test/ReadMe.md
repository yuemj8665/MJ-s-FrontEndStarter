
# 1. HTML 핵심요소 정리
## 1.1. 블록 요소
1. div
	- Division.
	- 특별한 의미가 없는 구분을 위한 요소.
    - 굉장히 많이 사용한다.
 2. h
	- Heading
	- 제목을 의미하는 요소
	- h1 ~ h6 까지 이용 가능, 숫자가 작으면 작을수록 더 중요한 제목을 의미한다.
3. p
	- Paragrap
	- 문장을 의미하는 요소
	- div로 작성해도 된다.
4. ul
	- Unordered List
	- 순서가 필요없는 목록의 집합을 의미
	- ol태그를 대신 쓸 수 있다.
	- ul태그의 자식은 li태그로 필수이다.
	- li
		- List Item
		- 목록 내 각 항목
		- li태그의 부모는 ul태그로 필수이다.

![블록요소 이미지](https://blogfiles.pstatic.net/MjAyMTExMjZfMTQ3/MDAxNjM3OTM0MDg3MzAz.H-XGQBZ-OpcAoJD4PgmWpl8eFv7FuEaAPAoQMUNagRwg.-1usBqdBWT7fohbazU3CroQ7aNNTau12gc565yYhlagg.PNG.yuemj/block.png?type=w1)


## 1.2 인라인 요소
1) img
	- 이미지를 삽입하는 요소
	- 경로 명시 필요(src)
	- 출력되지 않을 경우, 대신해서 출력 할 이미지의 이름 명시 필요(alt)
2) a
	- Anchor
	- 다른/같은 페이지로 이동하는 하이퍼 링크를 지정하는 요소
	- 링크를 건다.
	- 어디로 이동할 것인지 경로를 명확하게 지정(href)
	- target="_blank" -> 새 탭에 구글 페이지를 열리게끔 한다.
3) span
	- 특별한 의미가 없는 구분을 위한 요소(vs div)
	- 글자들의 범위를 잡아낼때 사용
4) br
	- Break
	- 줄바꿈 요소
	- <br/>
5) label
	- 라벨가능한 요소(input)의 제목

![인라인 요소 이미지](https://blogfiles.pstatic.net/MjAyMTExMjZfMTI4/MDAxNjM3OTM0MDg3MDIw.Rcv4faunlOlbxKlnkKv9D_kwLTbHKteQwN1Gmco4g0og.EhBH_3kEG0XclaYmz4WfALyetoL4v2VV2seF6iEAZAcg.PNG.yuemj/Inline.png?type=w1)

## 1.3 인라인/블록 Inline-block
- 인라인이면서, 블록이 가지고있는 몇가지 특성을 사용할 수 있다.
- 가로/세로 지정 가능, 마진/패딩 사용 가능
- 왼쪽에서 오른쪽으로 수평으로 쌓이는 특성을 사용한다.
1. input
	- 사용자가 데이터를 입력하는 요소
	- 입력받을 데이터의 타입(type)
	- 보통 사용은 text를 사용
	- 사용자에게 체크여부를 입력받음(checkbox)
		- 미리 체크를 하고싶다면(checked 속성)
	- 사용자에게 체크 여부를 그룹에서 1개만 입력받기(radio)
		- 체크박스와는 다르다.
		- 항상 기본적으로 그룹을 지어야하는 구조여야한다.
		- name이라는 속성으로 하나의 그룹이 된다.            
	- 사용자가 입력하기 전에 미리 입력된 값(value)
	- 사용자가 입력할 값(데이터)의 힌트(placeholder)
	- 입력요소 비활성화(disabled)
![인라인/블록요소 이미지](https://blogfiles.pstatic.net/MjAyMTExMjZfOTUg/MDAxNjM3OTM0MDg3NTg3.xjtQl03MwCdQP_GZ5bbXysvGnwzjt0eLnrwSH1DdD1gg.AuXe8tLEBBlBi_tcJX5wynHgGHaDK8TYN2ciFs61uhsg.JPEG.yuemj/inline_block_table.jpg?type=w1)
## 1.4 테이블 요소
1) table
	- 표 요소. 행row, 열column의 집합이다.
	- tr 행(row)
	- td 열(column), 테이블 데이터, cell

# 2. 전역속성
## 2.1. 전역속성 이란
	- <태그 title="설명"></태그>
	- 요소의 정보나 설명을 지정한다.

## 2.2. 스타일이란
    - <태그 style="스타일"></태그>
    - 요소에 적용 할 스타일(CSS)를 지정
    - link를 활용하여 가져온다던가, style태그를 선언하여 사용할 수 있음.

## 2.3. 클래스란
    - <태그 class="클래스"></태그>
    - 요소를 지칭하는 "중복이 가능한" 이름.
    - CSS 선택자를 위함.
    - 자바스크립트로 집어서 제어하기 위함.

## 2.4. ID
    - <태그 id="이름"></태그>
    - 요소를 지칭하는 고유한 이름
    - class와는 다른 점은 중복이 불가능하다.
    - 주요한 위치에 이름을 부여하기 위하여 사용.

## 2.5. Data
    - <태그 data-이름="데이터"></태그>
    - 요소에 데이터를 지정한다.

![전역속성 이미지](https://blogfiles.pstatic.net/MjAyMTExMjhfMTUw/MDAxNjM4MTA3NzE0MDc3.5aY4UhwlXANwBaiu-ebIRtuQBfHYsKpYoCTF31vUd1Eg.ZZf7no9idxu0ezQsDDSi6TXoH-9w3fltCE6C8vK1tZkg.PNG.yuemj/2021-11-28_All.png?type=w1)

# 3. CSS 선언 방식
## 3.1. 내장방식
    - <style></style>의 내용으로 스타일을 작성하는 방법
    - 장점 : 별도의 css파일을 만들지 않아도 html안에서 적용 가능하다.
    - 단점 : css내용이 점점 많아지면 html문서 안에서 쓰기 좋지않다.
    - 유지보수 차원에서 html/js/css는 나눠서 각자 파일을 관리하는게 좋다.

## 3.2. 인라인 방식
    - 요소의 style속성에 직접 스타일을 작성하는 방식(선택자 없음)
    - 장점 : 선택자를 굳이 추가 할 필요가 없다.
    - 단점 : 너무 지나치게 우선순위가 높다. 다른 소스에 의해서 변경이 쉽지가 않다.

## 3.3. 링크 방식
    - <link/>로 외부 css문서를 가져와서 연결하는 방식
    - 병렬방식

## 3.4. Import 방식
    - @import 규칙으로 css문서 안에서 또 다른 문서를 가져와 연결하는 방식
    - css문서에서 다른 css문서를 가져와서 연결 HTML - CSS(1) - CSS(2) (직렬 연결 방식)
    - HTML파일과 연결하기 위해서는 위의 CSS(1)이 연결되지 않는 이상 CSS(2)는 다른 방법이 없다.
    - 장점&단점 : HTML에 연결이 되서 CSS(1)내에 있는 import라는 소스가 분석되기 전까지는 CSS(2)는 HTML에 연결할 수 없다.
    - 일부러 연결을 지연시키기 위한 방법도 있다.
    - 하지만 지연이 되는것 자체가 단점이 된다.
![CSS 선언방식 이미지](https://blogfiles.pstatic.net/MjAyMTEyMDJfMTA4/MDAxNjM4NDQ2NzE4NTk0.vwM1zqCZDN8BGaOpA-vRqIMQGHEVHXaPwr2v3K3PvX8g.mI8YGutp-9HW_gi5TFyalcLT7AiDFT3LPEmB_348Ed8g.PNG.yuemj/2021-12-02_readme.png?type=w1)

# 4. 선택자

## 4.1. *
- 모든 요소를 선택한다.
```html
<style>
	* {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li>오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span>오렌지</span>
</div>
```
## 4.2. 태그 선택자
- ABC
- 태그 이름이 ABC인 요소를 선택한다.

```html
<style>
	li {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li>오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span>오렌지</span>
</div>
```
## 4.3. 클래스 선택자
- .ABC
- html class 속성의 값이 ABC인 요소를 선택한다
```html
<style>
	.orange {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li class="orange">오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span class="orange">오렌지</span>
</div>
```

## 4.4 아이디 선택자
- #ABC
- html id 속성의 값이 ABC인 요소를 선택한다.
```html
<style>
	#orange {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li id="orange" class="orange">오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span class="orange">오렌지</span>
</div>
```	

## 4.5. 복합 - 일치 선택자
- ABCXYZ
- 선택자 ABC와 XYZ를 동시에 만족하는 요소 선택
- 일치 선택자 작성 시, 태그 선택자를 선택해야 하는 경우 태그 선택자를 제일 먼저 적고난 후 이후에 적용한다.
```html
<style>
	span.orange {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li id="orange" class="orange">오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span class="orange">오렌지</span>
</div>
```	

## 4.6. 복합 - 자식 선택자
- ABC > XYZ
- 선택자 ABC의 자식요소 XYZ를 선택한다
```html
<style>
	ul > .orange {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li id="orange" class="orange">오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span class="orange">오렌지</span>
</div>
```	

## 4.7. 복합 - 하위(후손) 선택자
- ABC XYZ
- 선택자 ABC의 하위요소 XYZ 선택.
- **띄어쓰기**가 선택자의 기호이다.
```html
<style>
	div .orange {
		color: red;
	}
</style>
<div>
	<ul>
		<li>사과</li>
		<li>딸기</li>
		<li id="orange" class="orange">오렌지</li>
	</ul>
	<div>당근</div>
	<p>토마토</p>
	<span class="orange">오렌지</span>
</div>
<span class="orange">오렌지</span>
```	

## 4.8. 복합 - 인접 형제 선택자
- ABC + XYZ 
- 선택자 ABC의 다음 형제 요소 XYZ **하나**를 선택
```html
<style>
	.orange + li {
		color: red;
	}
</style>
<ul>
	<li>사과</li>
	<li>딸기</li>
	<li id="orange" class="orange">오렌지</li>
	<li>망고</li>
	<li>바나나</li>
</ul>
```

## 4.9. 복합 - 일반 형제 선택자
- ABC ~ XYZ 
- 선택자 ABC의 다음 형제 요소 XYZ **모두**를 선택
```html
<style>
	.orange ~ li {
		color: red;
	}
</style>
<ul>
	<li>사과</li>
	<li>딸기</li>
	<li id="orange" class="orange">오렌지</li>
	<li>망고</li>
	<li>바나나</li>
</ul>
```