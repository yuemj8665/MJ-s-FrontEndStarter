
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
![선택자1](https://blogfiles.pstatic.net/MjAyMTEyMDdfMjIx/MDAxNjM4ODc5ODYzMDA4.yhMNomoH-716UzIUDDSbktld9wRdLGwLQNjHNsSp2tog.Z4vhdf9m-WIAmpW7yXEbgEMsz1O45mh9SGlBLKAAqZsg.PNG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%90_1-1.png?type=w1)

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
![선택자2](https://blogfiles.pstatic.net/MjAyMTEyMDdfODYg/MDAxNjM4ODc5ODYzMjM1._iJoTz8mPxFdN-oNnG-FOhjsSiSTbtjvwx5qtUVx-gkg.9ySxb9MsuCqxDY2Fqi6Tab13TcEs4D__gNbiDkXbTgwg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%902-2.jpg?type=w1)

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
![선택자3](https://blogfiles.pstatic.net/MjAyMTEyMDdfODAg/MDAxNjM4ODc5ODYzODM2.7Dw2nKrNHJ-cC5h2uYPgqw27WuEsgI0dhoDlfyYXBQwg.joHqfSS3ddCrXvSaOs4byGWg3F3CSJ8umeZ840hi-Aog.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%903-2.jpg?type=w1)


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
![선택자4](https://blogfiles.pstatic.net/MjAyMTEyMDdfMjYy/MDAxNjM4ODc5ODY0MDE1.kiSJ_UkvUtODhWGRlhWQXCAL8b6sASDU0Y_Y3iKrgagg.JpKc-yuXq4I-8JsMqps9vdVVcs0XhO7dyVAoUiDv6zkg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%90_4-2.jpg?type=w1)


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
![선택자5](https://blogfiles.pstatic.net/MjAyMTEyMDdfMjEw/MDAxNjM4ODc5ODY0MjEz.TzZFOe_KcZLVjUbpkP25EnFYET9huDzgKccJx5ByGVAg.sfGg5sva3o9d2KtQ4nZFGLSyc9MoeWZjO6WJYPzx9Ngg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%90_5-2.jpg?type=w1)


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
![선택자6](https://blogfiles.pstatic.net/MjAyMTEyMDdfMjkg/MDAxNjM4ODc5ODY0Mzcy.-T88Y72VO9vtMthqIPqXxwJT9jHKge7HczeTUzYipNAg.IAqrtGqG3ww3YzIYQxoWGb17IIQTZwMgBpsUSPSJzJgg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%906-2.jpg?type=w1)


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
![선택자7](https://blogfiles.pstatic.net/MjAyMTEyMDdfMjE0/MDAxNjM4ODc5ODY0NTQx.yqm_mxCvlciY7Q0SVaoKaqyyu9sRCvRzRKllWIkkgQYg.xEQyp3npvkFAJoLYCYVxHjo4NJtW6MuoWytZBIMkpbQg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%90_7-2.jpg?type=w1)


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
![선택자8](https://blogfiles.pstatic.net/MjAyMTEyMDdfMTk3/MDAxNjM4ODc5ODY0NzY4.un1xDu5fzn7iknoIZ--q-yswGIRUi5yQwouq9YBmpB0g.nEKmTHU4dFYrlS6_knonIT37kRRSKzur17oMkVDxRIcg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%90_8-2.jpg?type=w1)


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
![선택자9](https://blogfiles.pstatic.net/MjAyMTEyMDdfMjky/MDAxNjM4ODc5ODY0OTYy.Yjp0lL2zJ2GxJuSWzvvJeUFus-DF46kHMoF8k--SVr0g.mZHG4UUZYi_u_3rvjKPFXPz7JEvang6BDD0cJNoGzscg.JPEG.yuemj/%EC%84%A0%ED%83%9D%EC%9E%90_9-2.jpg?type=w1)

## 4.10. 가상 클래스 선택자 - HOVER
- ABC:hover
- 선택자 ABC요소에 마우스 커서가 올라가 있는 동안 선택.
```html
<style>
	a:hover{
		color:red;
	}
</style>
<a href="https://www.naver.com">NAVER</a>
```
![선택자10](https://blogfiles.pstatic.net/MjAyMTEyMTJfMTYy/MDAxNjM5MzEwOTcyNTE0.ERos8z_f2-P8sYxkQTI7MzQofO8dFUDMYiHRLVrAD5Mg.eHwE4GzrzxdKDB5ugafqwYujov1yWfJRtp9L7xpezPcg.GIF.yuemj/4.10._hover.gif?type=w1)

## 4.11. 가상 클래스 선택자 - ACTIVE
- ABC:active
- 선택자 ABC요소에 마우스를 클릭하고 있는 동안 선택.
```html
<style>
	a:active{
		color:red;
	}
</style>
<a href="https://www.naver.com">NAVER</a>
```
![선택자11](https://blogfiles.pstatic.net/MjAyMTEyMTJfMTQ1/MDAxNjM5MzEwOTcyODkx.Ko_xX3pBiHv6bXdGw0AOSMkRpHXSBPWXDRwSosoAm4kg.UTLhfgkWp3cFWHF1iArtYaZL-4oqzuP3kpDxqu--ZpMg.GIF.yuemj/4.11._active.gif?type=w1)

## 4.12. 가상 클래스 선택자 - FOCUS
- ABC:fucus
- 선택자 ABC요소에 마우스를 클릭하여 focus가 되면 작동
```html
<style>
	input:focus{
		backgound-color:orange;
	}
</style>
<input type="text"/>
```
![선택자12-1](https://blogfiles.pstatic.net/MjAyMTEyMTJfMjUx/MDAxNjM5MzEwOTczMjE2.De6DzQ-QXEexYg_ovmdEk6SCFCGYd5C_ssXmSpiEb80g.F-55Kqnk1XEIqJQFPWy2Zkvyjp7GkYbaAqOjOUD03NUg.GIF.yuemj/4.12._focus1.gif?type=w1)
![선택자12-2](https://blogfiles.pstatic.net/MjAyMTEyMTJfMjEw/MDAxNjM5MzEwOTczNDI0.2hIeB4b0IL_atpoCvvycuXPdeKY9wirWXKuVU2RAJXQg.8K6eW-5cz0CyrwVVTI6ZHvqmmUwy--THNE5kMRkNlHkg.GIF.yuemj/4.12._focus2.gif?type=w1)

## 4.13. 가상 클래스 선택자 - FIRST CHILD
- ABC:first-child
- 선택자 ABC가 형제 요소 중 첫째라면 선택.
```html
<style>
	.fruits span:first-child{
		color : red;
	}
</style>
<div class="fruits">
	<span>딸기</span>
	<span>수박</span>
	<div>오렌지</div>
	<p>망고</p>
	<h3>사과</h3>
</div>
```

## 4.14. 가상 클래스 선택자 - LAST CHILD
- ABC:first-child
- 선택자 ABC가 형제 요소 중 마지막이라면 선택.
```html
<style>
	.fruits h3:last-child{
		color : blue;
	}
</style>
<div class="fruits">
	<span>딸기</span>
	<span>수박</span>
	<div>오렌지</div>
	<p>망고</p>
	<h3>사과</h3>
</div>
```

## 4.15. 가상 클래스 선택자 - NTH CHILD
- ABC:nth-child(n)
- 선택자 ABC가 형제 요소 중 n번째 자식을 선택.
- 2n이라면 0,2,4,6,8... 번쨰 자식을 선택한다.
- -n+3
```html
<style>
	.fruits *:nth-child(2n){
		color : orange;
	}
</style>
<div class="fruits">
	<span>딸기</span>
	<span>수박</span>
	<div>오렌지</div>
	<p>망고</p>
	<h3>사과</h3>
</div>
```

## 4.16. 부정 선택자
- ABC:not(XYZ)
- 선택자 XYZ가 아닌 ABC요소를 선택한다
```html
<style>
	.fruits *:not(span){
		color : puple;
	}
</style>
<div class="fruits">
	<span>딸기</span>
	<span>수박</span>
	<div>오렌지</div>
	<p>망고</p>
	<h3>사과</h3>
</div>
```

## 4.17. 가상 요소 선택자(Before)(Pseudo-Elements)
- ABC::before
- 선택자 ABC 요소의 **내부 앞**에 내용(Content)을 삽입한다
- Inline 요소를 추가한다
- 매우 자주 사용되는 요소이다.

```html
<style>
	.box::before{
		content: "앞!";
	}
</style>
<div class="box">
	Content!
</div>
```

## 4.18. 가상 요소 선택자(after)(Pseudo-Elements)
- ABC::after
- 선택자 ABC 요소의 **내부 뒤**에 내용(Content)을 삽입한다
- Inline 요소를 추가한다
- 매우 자주 사용되는 요소이다.

```html
<style>
	.box::after{
		content: "뒤!";
	}
</style>
<div class="box">
	Content!
</div>
```

## 4.19. 속성 성택자(ATTR)
- [ABC]
- 속성 ABC를 포함한 요소 선택
```html
<style>
	[disabled] {
		color: red;
	}
</style>
<input type="text" value="HAPPY">
<input type="password" value="1234">
<input type="tesxt" value="ABCD" disabled>
```

## 4.20. 속성 선택자(ATTR=VALUE)
- [ABC="XYZ"]
- 속성 ABC를 포함하고, 그 속성의 값이 XYZ인 요소 선택
```html
<style>
	[type="password"] {
		color: orange;
	}
</style>
<input type="text" value="HAPPY">
<input type="password" value="1234">
<input type="tesxt" value="ABCD" disabled>
```

# 5. 스타일 상속

## 5.1. 스타일 상속
- 스타일을 하위 자식에게 상속시킨다.
- 상속되는 CSS 속성들
	- 모두 글자/문자 관련된 속성들(모든 글자/문자 속성은 아님 주의)
		- font-style : 글자 기울기
		- font-weight : 글자 두께
		- font-size : 글자 크기
		- line-height : 줄 높이
		- font-family : 폰트
		- color : 색상
		- text-align : 정렬
		- ... 등등
	
- 예시
```html
<style>
	.animal{
		color: red;
	}
</style>
<div class="ecosystem">생태계
	<div class="animal">동물
		<div class="tiger">호랑이</div>
		<div class="lion">사자</div>
		<div class="elephant">코끼리</div>
	</div>
</div>
<div>식물</div>
```

## 5.2. 강제 상속
- 실제로 상속되지 않는 CSS 속성도 상속되게 만든다.
- 부모의 값을 가져와 상속받아 자동적으로 변경되게 만든다.
- 이는 사람으로서 실수 할 수 있는 상황을 최대한 줄이기 위해 사용한다.

# 6. 선택자 우선순위
## 6.1. 우선순위란
- 같은 요소가 여러 선언의 대상이 될 경우, 어떤 선언의 CSS속성을 우선 적용할지 결정하는 방법
- 점수가 높은 선언(명시도가 높은 선언)이 우선함.
- 점수가 같으면, 가장 마지막에 해석 된 선언이 우선한다.

## 6.2. 예시
```html
<style>
	div { color: red !important; }
	#color_yellow { color: yellow; }
	.color_green { color: green; }
	div { color: blue; }
	* { color: darkblue; }
	body { color: violet; }
</style>
<body>
	<div
		id="color_yellow"
		class="color_green"
		style="color: orange;">
		Hello World;
	</div>
</body>
```

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

	### 7.1.2. 단위
	1. px
		- 픽셀
		
	2. %
		- 퍼센트, 상대적인 백분율

	3. em
		- 요소의 기본적인 글꼴 크기
		- 1em = 10px
		- 역시 글꼴 크기라는 기준을 가지고있기 때문에 상대적

	4. rem
		- 루트 요소(html)의 글꼴 크기
		- 루트요소란 최상위 요소(html 등..)

	5. vw
		- 뷰포트 가로너비의 백분율
		- 뷰포트란 브라우저 페이지에 표시되는 전체의 영역

	6. vh 
		- 뷰포트 세로너비의 백문율

	7. 정리
	- em 단위의 기준은 해당 요소의 글자 크기 기준
	- 0px과 0vw중 더 큰 값은 같은 값

	### 7.1.3. 단축속성
	1. margin
		- 요소의 **외부** 여백(공간)을 지정하는 단축속성
		- 음수 사용 가능 (-10px)
		- 0 : 기본값, 외부여백 없음
		- auto : 브라우저가 여백을 계산한다. 가로(세로)너비가 있는 가운데 정렬에 활용한다.
		- 단위 : 위에서(7.1.2. 단위) 에서 지정했던 단위 사용
		- % : 부모 요소의 **가로너비**에 대한 비율로 고정
		- margin-top, margin-bottom, margin-left, margin-right으로 각 수치를 직접 지정가능하다.
		- margin은 뒤에 붙는 숫자의 수 만큼 상단, 우측, 하단, 좌측의 수치를 결정한다.
		![margin](https://blogfiles.pstatic.net/MjAyMjAxMDNfMjEw/MDAxNjQxMjE4OTc2NDAy.H2bzHaZ1qlsm8FGmaxdOSwpyj77NVlPizVI5hdiUp2Mg.XtlZVdjQOGIob_bIFUWKTygRKoAD2NrkiYU5GEpBSGIg.PNG.yuemj/2022-01-02_margin1.png?type=w1)
		- 정리
			- margin이란 요소의 바깥쪽에 존재하는 외부 여백이다.
			- margin: 40px 30px 20px; 의 30px은 왼쪽과 오른쪽 방향의 외부여백.

	2. padding
		- 요소의 **내부** 여백(공간)을 지정하는 단축속성
		- 요소의 크기가 커진다.
		- 0 : 기본값, 내부여백 없음.
		- 단위 : px, em, vw등 단위로 지정
		- % : 부모 요소의 가로 너비에 대한 비율로 지정
		- padding-top, padding-bottom, padding-left, padding-right으로 각 수치를 직접 지정가능하다.
		- padding은 뒤에 붙는 숫자의 수 만큼 상단, 우측, 하단, 좌측의 수치를 결정한다.
		![padding](https://blogfiles.pstatic.net/MjAyMjAxMDNfMTMw/MDAxNjQxMjIwNzg1ODc4.3g3l0YtuAulDguJho3L875lttpAtWcxM0zTH6VcssCEg.SzxN4BibGeoC96xmuOgPFwiLF81hY2-S8yu18_PAH68g.PNG.yuemj/KakaoTalk_20220103_233348817.png?type=w1)
		- 정리
			- padding이란 요소의 내부에 여백을 추가하는 역할
			- padding: 20px, 10px, 40px, 30px; 의 30px은 왼쪽 내부여백을 의미한다.
			- padding의 특징은 내부에 여백이 추가되기 때문에 요소의 크기가 그만큼 늘어나게 된다.

	3. border
		- 테두리의 두께, 종류, 색상을 결정.
		- 요소의 테두리 선을 지정하는 단축 속성
		- 요소의 크기가 커진다.
		- 선-두께 선-종류 선-색상;
		- border-width border-style border-color;
	***
	* border-width
		- medium : 기본값, 중간두께, 그러나 브라우저마다 기준이 다르기때문에 되도록 피하는게 좋다.
		- thin
		- thick
		- 단위 : px, em, % 등, 단위로 지정
		- border-width는 뒤에 붙는 숫자의 수 만큼 상단, 우측, 하단, 좌측의 수치를 결정한다.
		
		![border-width](https://blogfiles.pstatic.net/MjAyMjAxMDVfNDkg/MDAxNjQxMzA5MzQ1NzYx.JHujJ3VziWSPk9nclX6CTbx46xpei7GDu9LhMfebrnMg.5Lj4mAV_E182mKypNplDgYVkIiR9DS24E6B-5M5lsu8g.PNG.yuemj/width.png?type=w1)
	***
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
	***
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
	***
	* border-방향, border-방향-속성
		- 요소의 테두리 선을 지정하는 기타 속성들
		- border-top-width : 위쪽 선의 두께
		- border-left-stlye : 왼쪽 선의 종류
		- border-right-color : 오른쪽 선의 색상 등...
	***
	* 정리
		- border 속성의 특징 : padding과 동일하게 요소의 크기가 늘어난다.

		![borderResult](https://blogfiles.pstatic.net/MjAyMjAxMDVfMjgy/MDAxNjQxMzA5MzI1NzY2.S9daliseBd-G8DpOP0nfLXAIbX0iYSJkBR_XkP0av1wg.yVKl1C0fDWtlh0uJ3On9M2_jQQNJENrZ_GUhqdAdSRkg.PNG.yuemj/PRACTICE.png?type=w1)
	
	* border-radius
		- 0 : 기본값, 둥글게 없음
		- 단위 : px,me,vm 등 단위로 지정.
		- border-radius 뒤에 붙는 숫자의 속성만큼 각 모서리의 둥근 정도를 결정 할 수 있다.

		![borderRadius](https://blogfiles.pstatic.net/MjAyMjAxMDVfOTgg/MDAxNjQxMzkxNjAyOTY4.WLGitbcytfWkHh17LLunoabMnDpWoMhAAiR3hRzjKhQg.JxTwMYRhUqJPuWc4ZWWyu55P1Egn_POaSDZAfA4X778g.JPEG.yuemj/2022-01-05_radius.jpg?type=w1)
	
	4. box-sizing
	- 요소의 크기 계산 기준을 지정
	- content-box : 기본 값, 요소의 내용(content)으로 크기 계산
	- boarder-box : 요소의 내용 + padding + border로 크기 계산

	5. overflow
	- 요소의 크기 이상으로 내용이 넘쳤을 때, 보여짐을 제어하는 단축 속성
	- visible : 기본값, 넘친 내용을 그대로 보여줌
	- hidden : 넘친 내용을 잘라낸다.
	- scroll : 넘친 내용을 잘라냄, 스크롤 바 생성
	- 넘친 내용이 있는 경우에만 잘라내고 스크롤 바 생성
	
	* 요소 이상으로 내용이 넘쳤을 때, 보여짐을 제어하는 개별 속성들
		- overflow-x : 가로
		- overflow-y : 세로

	5. disply
	- 요소의 화면 출력(보여짐) 속성
	- 각 요소에 이미 지정되어 있는 값
		- block : 상자(레이아웃) 요소. (div)
		- inline : 글자 요소 (span)
		- inline-block : 글자 + 상자 요소 ()
	- 따로 지정해서 사용하는 값'
		- flex : 플렉스 박스(1차원 레이아웃)
		- grid : 그리드 (2차원 레이아웃)
		- none : 보여짐 특성 없음, 사라짐.
	- 기타 : table, table-row, table-cell 등등..
	- 정리 : HTML Inline 요소에 가로너비를 인위적으로 변경하기 위해서는 display: block;
	같은 요소를 사용한다.
	  
	6. opacity
	- 요소 투명도
	- 1 : 기본값, 불투명
	- 0.x : 투명도

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

	### 7.2.5. font-family
	- 글꼴(서체) 지정
	- 글꼴, "글꼴2", ... 글꼴 계열(serif)
	- 글꼴 계열 : 필수로 작성.
		- serif : 바탕체 계열
		- sans-serif : 고딕체 계열
		- monospace : 고정너비(가로폭이 동등) 글꼴 계열
		- cursive : 필기체
		- fantasy : 장식 글꼴 계열
	- 띄우쓰기 등, 특수문자가 포함된 글꼴 이름은 큰 따옴표로 묶어야 한다.
	- 글꼴의 후보 지정하는 이유는 브라우저가 사용 할 수 있는 글꼴들의 우선순위로 시도한다.
	- 글꼴 후보들을 전부 사용 할 수 없는 상황이라면, 마지막의 작성 된 필수값인 글꼴 계열을 사용한다.
	  
	

	## 7.3. 배경
	- 요소의 배경 색상이나 이미지 삽입으로 제어 가능

	## 7.4. 배치
	- 요소를 내가 원하는 위치에 배치 제어

	## 7.5. 플렉스(정렬)
	- HTML의 요소는 위에서 아래로 쌓이는 수직적으로 되지만, 수평적으로 제어할 수 있는 속성.

	## 7.6. 전환
	- 요소의 전/후 상태를 애니메이션 처리한다.
	- 굉장히 많이 사용된다.

	## 7.7. 변환
	- 요소의 변환 효과. 요소를 회전, 이동, 크기조절해주는 CSS의 속성
	- 2D변환과 3D변환이 있다.

	## 7.8. 띄움
	- 요소를 띄우게 되면 요소 주변에 문자가 흐를 수 있게 되어있음
	- Ex) 신문

	## 7.9. 애니메이션
	- 전환과는 다르게 조금 더 복잡한 구조의 애니메이션을 만들어서 연출을 할 수 있다.

	## 7.10. 그리드
	- 행과 열의 구조를 가지고있는 2차원의 레이아웃을 만들기 위해서 만든다.
	- 복잡하게 보이는 구조를 쉽게 진행할 수 있다.

	## 7.11. 다단
	- 하나의 페이지에서 단을 여러개를 나눠서 사용 할 수 있다.

	## 7.12. 필터
	- 블러, 흑백효과, 반전 등 CSS로 필터를 적용 할 수 있다.


