## 1.8.17. position-3
1. z-index
    - 요소의 쌓임 정도를 지정한다.
    - auto : 기본값, 부모 요소와 동일한 쌓임 정도, 0
    - 숫자 : 숫자가 높을수록 위에 쌓이게 된다.
    - z-index는 1씩 증가하도록 유지보수를 하는게 좋다.
    
2. 요소의 display가 변경된다.
    - **position 속성의 값으로 absolute, fixed가 지정된 요소는 display속성이 block으로 변경된다.**
    - 결과적으로 아래의 두 css는 같다.
    ```css
    css1 {
        display : block;
        position: absolute;
        top: 30px;
        left: 30px;
        z-index: 1;
   }
   
   css2 {
        position: absolute;
        top: 30px;
        left: 30px;
        z-index: 1;
    }
    ```
   
3. 정리
   - position의 기본값은 static
   - 위치상 부모 요소를 기준으로 배치하는 position 속성의 값은 absolute
   - 뷰포트를 기준으로 배치하는 position 속성의 값은 fixed