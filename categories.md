---
layout: archive-taxonomies
type: categories
title: Projects
permalink: /projects/
---   
<style>
.center-text {
  text-align: center;
}
</style>
 
<div class="taxonomies-wrapper">
  <ul class="taxonomies">
    <li><a class="taxonomy" href="#wwc">
      <span>WWC</span>
      <span class="taxonomy-count">chatting platform</span>
    </a></li>
    <li><a class="taxonomy" href="#potion">
      <span>Potion Shop</span>
      <span class="taxonomy-count">shopping mall</span>
    </a></li>
  </ul>
</div>
  <h2 class = "center-text" id="wwc">WWC</h2>  
  <p class = "center-text">전 세계 어디서든, 언어의 장벽 없이, 누구와도 대화가 가능한, 새로운 채팅 플랫폼</p>
  <p class = "center-text">(2023.07 ~ 2023.09 개발 중)</p>
 
[`github 바로가기`](https://github.com/bonugg/WorldChatProject)<br/>   
  
![gif](wwcmain.gif){: width="650px" height="400px"}<br/>  
<p class = "center-text">&#128071; my role &#128071;</p> 

![gif](cateChat.gif){: width="650px" height="400px"}<br/> 
<p class = "center-text">단체 관심사 채팅(category chat)</p>  

- 총 열 세 개의 카테고리 별 채팅방 분류
- 방 이름, 최대 인원수, 카테고리 선정 후 채팅방 개설 가능
- 채팅방을 개설한 유저(방장)은 채팅방 자동 입장
- 입장 시 '입장 메시지' 표출

![gif](cateChatting.gif){: width="650px" height="400px"}<br/>
<p class = "center-text">실시간 메시지 전송 & 자동 번역</p>

- 웹소켓을 이용한 실시간 메시지 전송 가능
- 언어 설정 시, 상대 유저의 언어를 자동으로 감지하여 내가 설정한 언어로 자동 번역(papago translation api, papago detection api)
- 단체 채팅의 특성 상 여러 언어가 오가는데, 이때 자동 번역 기능을 설정하면 유용할 것으로 예상


![gif](pay.gif){: width="650px" height="400px"}<br/>
<p class = "center-text">파일 전송 & 다운로드</p>

- 웹소켓을 이용한 실시간 파일 전송 가능
- 전송한 파일은 ncloud의 object storage에 저장
- 파일 다운로드 가능


<hr>
<h2 class = "center-text" id="potion">Potion Shop</h2>
<p class = "center-text">초능력을 판매하는 포션 쇼핑몰 '포션이었다'</p>
<p class = "center-text">(2023.06 ~ 2023.07 개발 완료)</p>

[`github 바로가기`](https://github.com/three-team1/main/tree/main)<br/>   
    
![gif](potion.gif){: width="650px" height="400px"}<br/>
<p class = "center-text">&#128071; my role &#128071;</p>  

![gif](qna.gif){: width="650px" height="400px"}   
<p class = "center-text">QNA 게시판</p>

- CRUD 기능 구현 
- 게시글 제목과 해당 게시글의 댓글 갯수를 같이 표출
- 새로고침 시 조회수 상승 방지 기능
- 제목과 내용으로 게시글 검색 가능 

![gif](cart.gif){: width="650px" height="400px"}<br/>
<p class = "center-text">장바구니</p>

- 전체 주문/선택 주문에 다른 상품 개수와 총 금액 표출
- +, -으로 수량 조절
- 수량에 따른 금액 상승 또는 감소
- 장바구니 물품 삭제 가능
- 주문하기 버튼 클릭 시 결제페이지로 이동

![gif](pay.gif){: width="650px" height="400px"}<br/>
<p class = "center-text">결제페이지</p>

- 내 배송지 입력 버튼 클릭 시 회원가입 시 입력한 회원 정보를 자동으로 불러옴
- 배송지 정보 직접 입력 가능
- 이전 장바구니 페이지에서 주문한 상품과 수량, 금액 표시
- 카드 결제 가능
- 결제하기 버튼을 누르면 결제창으로 이동(아임포트 API - NHN KCP 사용)

  