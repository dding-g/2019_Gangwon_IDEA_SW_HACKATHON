## 📌2019 강원 아이디어 해커톤
### 주최
* 3개 학교 SW사업단의 공동 주최
  - 한림대학교 SW 중심 사업단
  - 강원대학교 SW 중심 사업단
  - 연세대학교 미래캠퍼스 SW 중심 사업단
### 🚕 강원 시장가장
* __강원도 재래시장 이용률을 높이기 위해 아이디어 제시 및 설계를 진행한 프로젝트__
---
### 📕팀원
* 조명근
* 장경수
* 이용하
* 최승명
* 황영조
---
### 🚗아이디어 내용

* 재래시장 활성화를 위한 아이디어

* 기존 문제점

  * 다른 배달 어플 등 기존의 플랫폼에 비해 경쟁력이 떨어짐.
  * Pick-up 을 원칙으로 하지만 결제시 마일리지와 같은 시스템이 없음.
  * 유명한 곳은 주문 후 대기시간이 있음. 이로 인해 시장이 필요 이상으로 붐비는 경우가 많음.
  * 재래시장의 특성상 기존의 지도 Application에 표시되지 않는 부분이 있음. 점포를 찾기가 어려움. 

* 기본 틀

  1.  점포별 판매량에 따라 할인율을 조정해서 잘 팔리지 않는 곳은 다른곳에 비해 할인률을 높인다.
  2.  Application은 회원제로 운영된다. : 실명제와 카카오톡 플러스 친구 API 사용을 위한 전화번호 정보 및 기타 관광지에서 정보활용을 위함
      1.  지역별 점포 현황, 점포별 할인율을 지도에 반영 및 표현
      2.  어플을 활용하여 구매 시 마일리지가 쌓임. 마일리지는 해당 지역의 다른 관광지에서 사용 가능
  3.  카카오톡 플러스 친구 API를 활용하여 예상 대기시간과 주문한 음식이 완료되면 알려줌.

  * 스마트폰을 이용해서 번호표 시스템 (시장 현황을 보여주면서 마일리지나 지역화폐를 얼마나 주는지도 같이 출력)
  * 실행 과정
    1.  포스기에서 계산
    2.  QR코드 찍으면 해당 데이터와 함께 서버로 전송. QR코드 안찍어도 주문이 어떻게 들어갔는지 알아야 하기 때문에 서버로 전송
    3.  서버에서 QR코드로 찍은 데이터가 들어오면 해당 QR코드를 가진 사람에게 몇 번째 순서 인지 데이터 전송. ( 주문하지 않은 사람들도 해당 점포에 사람이 얼마나 있는지 알아야 하기 때문에 어플에서 주문 현황을 실시간으로 볼 수 있게 제작 )
    4.  예상 시간을 보여주고 만약, 예상 시간보다 빨리 음식이 만들어 졌으면 해당 점포에서 완료 버튼을 누름
    5.  완료 되었다고 사용자의 Application 으로 알려줌
  * 마일리지나 지역화폐가 아니면 할인률로 커버하고 지역 사회가 할인률을 커버치기.
  * 예상 대기시간 확인 - 주문 - 선결제 - 결제하고 사장이 수동으로 입력 (걸리는 시간, 등) - 번호표 (APP)  - 대기시간을 카카오톡 채널로 알려줌 - 수령
    * 카카오채널로 대기 시간 알림
    * 점포별로 등록된 대기자수 비교, 계산(AI) - 대기자수 적은 또는 없는 점표로 유도 - 유도요령(ex 할인률)

---

### 🥕 기대 효과

1. **할인율 제공으로 비인기 점포 활성화**
2. **시장 명물 메뉴 추천과 메뉴에 맞는 점포 검색**
3. **시장 점포 번잡도 제공을 통한 쉬운 점포 상황 파악**
4. **매장 앞에서 기다리지 않아도 되는 번호표 시스템으로 회전율 증가**

---

### ⚙ 시스템 설계

- System Architecture
  - ![System Architecture_아이디어해커톤_1](https://user-images.githubusercontent.com/29707967/82056984-aa85a900-96fd-11ea-8763-7755372dbcb3.png)
- Procedure
  - ![Procedure_아이디어해커톤.jpg](https://github.com/dding-g/2019_Gangwon_IDEA_SW_HACKATHON/blob/master/Procedure_%EC%95%84%EC%9D%B4%EB%94%94%EC%96%B4%ED%95%B4%EC%BB%A4%ED%86%A4.jpg?raw=true)
- DB Schema
  - ![image](https://user-images.githubusercontent.com/29707967/82057271-0cdea980-96fe-11ea-8748-097b588543c8.png)
- 간단 디자인
  - ![image](https://user-images.githubusercontent.com/29707967/82057352-2da6ff00-96fe-11ea-8f99-f38177fa6f76.png)

---

### 🏅 대회 결과

<center><img src="https://github.com/Yossarian92/2019_Gangwon_IDEA_SW_HACKATHON/raw/master/Images/photo5.jpg" width="600" height="800"></center>
<center><img src="https://github.com/Yossarian92/2019_Gangwon_IDEA_SW_HACKATHON/raw/master/Images/photo4.jpg" width="800" height="600"></center>
<center><img src="https://github.com/Yossarian92/2019_Gangwon_IDEA_SW_HACKATHON/raw/master/Images/photo1.jpg" width="1000" height="600"></center>
