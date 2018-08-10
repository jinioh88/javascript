# 지도
## 개요
  - 구글 맵 API를 활용해 지도를 만들자. 

## 사전학습 - AJAX
  - 지도 데이터를 불러오기 위해 서버와 통신이 필요하다.
  - 서버에 있는 데이터를 요청하는 방법을 알아보자.
  - AJAX는 비동기 통신 처리(콜백함수)를 의미하며, 자바스크립트를 이용해 서버와 데이터를 주고 받는 방식이다. 
  - 웹 페이지 특정 영역에만 필요한 내용을 갱신할 수 있다.
  - 데이터 전송 형식
    - 서버와 데이터를 주고 받을 때 쓰는 자료 형식 중 대표적인 것이 XML, JSON이 있다. 
    - $.ajax() 메서드
      >
        $ajax({
            url: '가져올 파일명',
            dataType: '데이터 형식',
            success: function(){
                // 콜백 함수(가져온 파일에 대한 처리)
            }
        }); 
        
## 서버 환경 구축
   - AJAX는 http프로토콜을 통해 서버와 통신하므로 서버 환경이 필요하다. 
   - XAMPP 를 설치 하자.
     