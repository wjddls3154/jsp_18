# jsp_18 : jquery 이용 2 (Atom에서만 됬음)

![image](https://user-images.githubusercontent.com/37132897/158184416-5d6f3bdf-6be1-40cd-92e9-4bc241fbc1d1.png)
- 버튼 누르기 전

![image](https://user-images.githubusercontent.com/37132897/158184443-9f743246-6cd0-465f-bc19-f45b3ceffb91.png)
- 버튼 누른 후 : 인덱스 1,3,5 (홀수) 만 변경됨.


      $('#two').click(

      function f() {
      
        $('h1:odd').html('반갑습니다~!!!!'); // jquery 사용 3, odd : 홀수(1,3,5)만 변경
        
      }
      
      );
      
      // $(#id) : id만 선택   Ex) 'h1.one#four' : h1에 one 클래스와, id가 four 이 있으면 해당.
      
      // $(.class) : class만 선택   Ex) 'h1.one.three' : h1 클래스에 one과, three가 있으면 해당.
      
      // $(h1.class) : h1에 class의 조합이 된 엘리먼트를 선택
      
      // $(h1.classone.classtwo#idone#idtwo)

      // 필터(기본 필터, 속성 필터, 차일드 필터, 컨텐츠 필터)
      
      // :even
      
      // :odd 홀수만
      
      // :first   Ex) 'h1:first'
      
      // :last    Ex) 'h1:last'
      
      // :nth-child(2)
      
      // :nth-child(2n)
      
      // :etc
