# woowa-userstory-2020

최근 구매 목록(장바구니)을 통해 만들 수 있는 음식의 레시피를 추천하고 필요한 재료를 판매하는 서비스

### 요구사항
**1. 1순위 Persona 제작**
- 사용자(구매자)
- 38세
- 7년차 전업주부  
  
**Needs**
- 남은 재료를 사용하여 질리지 않도록 새로운 요리를 시도하고 싶다.
- 전에 구입했던 식재료들이 쌓이지 않도록 남은 식재료를 활용하고 싶다.
- 레시피에서 부족한 식재료만 필요한만큼 주문하고 싶다.
<br/>

**2. 이를 기반으로 시나리오를 작성**

|제품|페르소나|시나리오|
|---|---|---|
|레시피 추천|판매자|- 사용자의 장바구니를 기반으로 레시피 추천하기<br/>- 음식 제작 과정을 보여주는 동영상 제공하기|
|구매 플랫폼|판매자|- 레시피를 보여주면서 사용자가 필요한 재료를 구매할 수 있도록 하기|
|구매 플랫폼|사용자|- 부족한 식재료 선택하기<br/>- 선택한 식재료의 필요 수량 입력하기<br/>- 식재료 구매하기|

>가족을 위한 저녁 메뉴를 고민하던 김OO씨는 '메뉴를 부탁해(가제)'에 접속한다.
>어플리케이션에서 1주일 내에 구입한 재료를 바탕으로 추천한 다양한 메뉴를 둘러본다.
>추천 메뉴 중 소고기 무국을 선택하고, 제공된 레시피를 본다.
>레시피를 보면서 소고기와 파가 조금 부족하다는 것을 깨닫고 부족한 양만큼 구매했다.
>주문한 식재료가 도착하고 레시피와 함께 제공된 동영상을 보면서 요리를 시작한다.

<br/>

**3. 시나리오에서 요구사항 도출**

|시나리오|요구사항|
|---|---|
|어플리케이션에서 1주일 내에 구입한 재료를 바탕으로 추천한 다양한 메뉴를 둘러본다.|- 1주일 내에 구입한 물품들을 관리해야한다.<br/>- 장바구니를 기반으로 만들 수 있는 메뉴를 추천해야한다.|
|추천 메뉴 중 소고기 무국을 선택하고, 제공된 레시피를 본다.|- 제공된 레시피 중에 만들 음식을 선택할 수 있어야 한다.<br/>- 음식에 필요한 재료를 알려줘야한다.|
|레시피를 보면서 소고기와 파가 조금 부족하다는 것을 깨닫고 부족한 양만큼 구매했다.|- 부족한 식재료를 구매하는 기능이 있어야한다.<br/>- 필요한 수량을 입력할 수 있도록 해야한다.<br/>- 부족한 식재료를 구매할 수 있어야한다.|
|주문한 식재료가 도착하고 레시피와 함께 제공된 동영상을 보면서 요리를 시작한다.|- 레시피와 함께 관련 동영상이 제공돼야한다.|
<br/>