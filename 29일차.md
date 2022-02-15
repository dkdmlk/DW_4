header: 메뉴(navigation)도 오고 머리글, 사이트로고 
~~~css
img {
        max-width: 100%;
      }
      .card {
        width: 300px;
        height: 200px;
        margin: 0px auto;
        position: relative;
      }
      .card1 {
        width: 200px;
        transition: 5s;
      }
      .card2 {
        position: absolute;
        width: 400px;
        top: 0px;
        left: 0px;
        display: none;
      }
      .card:hover .card2 {
        display: block;
        cursor: pointer;
      }
~~~
이미지를 겹쳐 포인트를 누를시 다른이미지로 교체
<!-- 링크태그를 마치 버튼처럼 -->
<!-- #:이동할 사이트가 없다 -->
아이템에 flex:1을하면 아이템들이 동일한 크기를 가지게 됨.
 /* none의 반대는 black */