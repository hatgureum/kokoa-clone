1. css가 하는 일=html을 가리키는 일.  
이렇게 가리키는 걸 selector라고 한다.

2. css 속성에는 빈칸, 밑줄, 슬래쉬 사용 못함.  하이픈, 붙임표만 써야함.

3. css:Cascading Style Sheets.  Cascading이란 '위에서 아래로 흐르는', '상속 또는 종속하는'.  
=브라우저가 css를 읽을 때 위에 있는 코드부터 차례대로 읽는다.  

4. 그렇기 때문에 항상 '마지막'에 있는 명령어가 최종적으로 실행된다. 예를 들어 똑같은 h1태그에 대해 외부 css파일에서 먼저 색을 빨강이라고 했다가 html에서 나중에 파랑이라고 하면 최종 결과물은 파랑이 된다.  

반대로 css link 코드를 html의 style 부분보다 아래에 넣으면 css 파일의 내용이 적용된다.  

5. 속성이 겹치지 않으면 한 태그의 속성을 여러 번 나눠서 지정하는 것도 가능하다.  

예를 들어 h1{ color:red } 해놓고 다시 h1{font-size:40px}이라고 해도 다 적용된다.  

3.3  
- 옆에 다른 요소가 올 수 없는 것들을 block, 있는 것들을 inline(in the same line)이라고 한다.  

- block에 해당하는 것들, 예를 들어 div는 요소의 옆에 다른 요소가 올 수 없다. 무조건 아래로 나열된다.(header, main, section, paragraph 등도 그렇다?)  

- 반면 inline인 것들, 예를 들어 span,a,image는 옆에 올 수 있어서 옆으로 나열된다.

- 대부분의 box는 block이다.  

3.4.
- display 속성: block을 inline으로, 또 반대로도 가능하게 해주는 것.

