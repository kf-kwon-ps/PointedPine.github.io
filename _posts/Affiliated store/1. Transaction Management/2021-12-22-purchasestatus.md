---
title:  "매입 현황 조회"
excerpt: "검색 조건을 입력하여 매입 현황을 조회합니다"

categories:
  - affliated TM
tags:
  - [가맹점, 매입 현황 조회]

toc: true
toc_sticky: true
 
date: 2021-12-29
last_modified_at: 2021-12-29
---
### 거래 관리 - *매입 현황 조회*
![가맹점 매입현황조회](https://user-images.githubusercontent.com/95394003/147629993-ec522f9e-4e87-460f-8dbc-47cd4d13914d.jpeg)

#### *구분* <br>
**< 검색 조건 >** **(22)**<br>
승인번호, 매입번호, 가맹점명<br>거래일자/지급일/정산예정일/입금예정일, 승인금액, 리스크,<br>터미널 번호, 카드BIN, 카드뒤4자리, 매입구분, 정산상태,정산주기,<br>일시불/할부, 신용/체크, 매입사, 가맹점 대표자, VAN,<br>취소구분, 취소원거래번호, 거래번호, 가맹점 ID, 입금상태
<br>

**< 조회 결과 항목 >** **(18)**
<br>체크박스, No, 거래일시, 승인번호, 매입번호, 거래번호, 가맹점,<br> 가맹점대표, 주문번호, 터미널ID, 매입구분, 신용/체크, 취소거래,<br> 금액, BIN, LAST4, 할부, 리스크
<br>
<br>

#### *Description*
- 검색 조건을 입력하여 거래건별 승인내역 등 매입 현황을<br>조회합니다.
- 조회 결과 항목 중 매입 번호를 통해 매입정보, 취소요청,<br>KSPAY 영수증 조회 등 매입내역에 대한 상세 정보를<br>확인할 수 있습니다.
- KSPAY 영수증 조회를 클릭하여 조회 및 VAN 매출전표를<br>출력할 수 있습니다.

#### *Detail*
<br>

![image](https://user-images.githubusercontent.com/95394003/146481772-129ea77c-27de-4d95-84df-cc3dd5c0a795.jpeg)
###### 승인번호
거래 승인번호를 입력합니다.

###### 매입번호
거래 매입번호를 입력합니다.

###### 가맹점명
거래가 발생한 가맹점의 이름을 입력합니다
<br>
<br>

![거래일자](https://user-images.githubusercontent.com/95394003/146482288-281b97a7-3e60-4c56-b40a-b5889a1299c7.jpeg)
###### 거래일자
거래일자에 대한 조회 기간을 설정합니다.<br>날짜부터 날짜로 설정 가능합니다.

###### 지급일
지급일에 대한 조회 기간을 설정합니다.<br>날짜부터 날짜로 설정 가능합니다.

###### 정산예정일
정산예정일에 대한 조회 기간을 설정합니다.<br>날짜부터 날짜로 설정 가능합니다.

###### 입금예정일
입금예정일에 대한 조회 기간을 설정합니다.<br>날짜부터 날짜로 설정 가능합니다.
<br>
<br>

![지사 승인금액 리스크](https://user-images.githubusercontent.com/95394003/147440848-18497c58-dec9-494f-a31e-e69c64973887.jpeg)
###### 승인금액
거래가 승인된 금액의 범위를 설정합니다.<br>금액부터 금액으로 설정 가능합니다.

###### 리스크
리스크 종류를 선택합니다.<br>
전체, 건한도, 중복, 고액, 최소금액, 야간할부, 1일중복, 주간할부,<br> 야간건한도, 위험, 관리자설정
<br>
<br>

![지사 터미널번호부터 정산](https://user-images.githubusercontent.com/95394003/147441145-bad576a9-a7c3-4fff-b6d1-c8fb415994aa.jpeg)
###### 터미널 번호
터미널 번호를 입력합니다.

###### 카드 BIN
카드의 정보를 구분할 수 있는 BIN 번호를 입력합니다.<br>
카드번호의 첫번째 자리부터 여섯번째 자리까지 입력합니다.

###### 카드뒤4자리
카드번호 끝 4자리를 입력합니다.

###### 매입구분
매입에 대한 구분을 전체, 매입, 매입취소 중에 선택합니다.

###### 정산상태
정산에 대한 상태를 선택합니다.<br>
전체, 대기, 확정, 보류, 완료 중에 선택합니다.
<br>
<br>

![정산주기](https://user-images.githubusercontent.com/95394003/146488198-6ca8c161-13e2-48b5-825d-f89fe582569b.jpeg)
###### 정산주기
정산주기를 선택합니다. (D+0~7, C+0~7, A+1, B+1)
<br>
<br>

![지사 일시불부터끝](https://user-images.githubusercontent.com/95394003/147441230-0b2b6c98-46ed-43de-8e11-be7868fcbde0.jpeg)
###### 일시불/할부
거래가 일시불인지 할부인지를 선택합니다.

###### 신용/체크
결제한 카드가 신용카드인지 체크카드인지를 구분합니다.

###### 매입사
결제한 카드 매입사를 선택합니다.<br>
(전체, 국민, 농협, 롯데, 비씨, 삼성, 하나, 현대, 기타)

###### 가맹점 대표자
가맹점 대표자를 입력합니다.

###### VAN
VAN 종류를 선택합니다.

###### 취소구분
취소구분을 선택합니다. 전체와 부분으로 구분됩니다.

###### 취소원거래번호
취소원거래번호를 입력합니다.

###### 거래번호
거래번호를 입력합니다.

###### 가맹점 ID
가맹점 ID를 입력합니다.

###### 입금상태
입금상태를 선택합니다. 전체, 입금대기, 입금완료로 구분됩니다.

<br>
<br>

![조회결과](https://user-images.githubusercontent.com/95394003/146479953-2adedabb-d3a8-4b89-9aa9-31b72fe795e4.jpeg)
###### 체크박스
리스크를 변경하고자 하는 매입내역에 체크할 수 있습니다.

###### No
조회된 결과의 리스트 번호를 나타냅니다.

###### 거래일시
거래가 이루어진 날짜와 시간을 나타냅니다.

###### 승인번호
거래의 승인번호를 나타냅니다.
<br>
<br>

![image](https://user-images.githubusercontent.com/95394003/147442074-d093c8d0-b87d-4029-aa27-84a1eeda66ad.png)
###### 매입번호
매입번호를 나타냅니다.<br>클릭하면 매입내역에 대한 상세정보를 확인할 수 있습니다. <br>
매입 정보를 조회하고 취소를 요청할 수도 있습니다.

###### 거래번호
거래번호를 나타냅니다.

###### 가맹점
거래가 이루어진 가맹점을 표기합니다.

###### 가맹점대표
해당 가맹점의 대표자 이름을 나타냅니다.

###### 주문번호
주문 번호를 나타냅니다.

###### 터미널ID
터미널 ID를 나타냅니다.

###### 매입구분
매입에 대한 구분을 나타내는데 매입과 취소로 구분됩니다.

###### 신용/체크
거래한 카드가 신용카드인지 체크카드인지를 나타냅니다.

###### 취소거래
취소 거래일 경우 취소거래번호를 나타냅니다.

###### 금액
거래 금액을 표기합니다.

###### BIN
카드의 정보를 구분할 수 있는 BIN 번호를 나타냅니다.<br>
카드번호의 첫번째 자리부터 여섯번째 자리까지 보여줍니다.

###### LAST4
카드번호 끝 4자리입니다.<br>
암호화가 되어있을 수도 있습니다.

###### 할부
할부 기간을 나타냅니다.<br>
일시불 거래일 경우 00으로 표기됩니다.

###### 리스크
리스크를 구분해서 나타냅니다. 