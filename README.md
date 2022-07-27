# 스니프로 (SniffPro)  
*반려동물 종합 포털 시스템(나만 없어 반려동물)    
*사용IDE: Eclipse(ver.2022.03), Sql Developer  
*사용기술: Spring,Java,Oracle,BootStrap  
*소요기간: 2022.06.17~
  
*데이터베이스 업무정리  
  1.회원은 본인의 개인 정보를 시스템에 등록하며, 일반 회원과 관리자로 구분된다.  
  2.관리자는 판매할 상품을 시스템에 등록한다.  
  3.회원은 원하는 상품을 주문할 수 있으며 주문한 상품은 장바구니에 담을 수 있다.  
  4.회원이 주문한 상품의 주문 상태가 완료라면 상품에 대한 후기를 작성할 수 있다.  
  5.회원이 상품을 주문하면 상품의 재고가 차감된다. 재고가 없으면 상품은 품절된 상태이며 장바구니에 담을 수 없다.  
  6.메뉴에는 게시판을 구분하는 대메뉴가 있으며 각 대메뉴마다 소메뉴가 존재한다.  
  7.게시판마다 게시글을 작성할 수 있으며, 회원의 권한에 따라 게시글 작성의 유무가 달라진다.  
  8.게시글은 등록, 수정, 삭제, 조회가 가능하다.  
  9.각 게시글에 댓글을 등록할 수 있으며 수정, 삭제가 가능하다.


*테이블 관계도  

![테이블관계도(최종)](https://user-images.githubusercontent.com/52398783/175249238-22cadde0-418d-4ad0-8645-a57c7d9611fd.png)
