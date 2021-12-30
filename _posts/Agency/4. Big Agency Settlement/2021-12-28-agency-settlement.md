---
title:  "에이전시 정산 조회"
excerpt: "검색 조건을 입력 및 선택하여 에이전시에 대한 정산 정보를 조회합니다"

categories:
  - agency settlement
tags:
  - [에이전시, 대행사 정산 조회]
toc: true
toc_sticky: true
 
date: 2021-12-16
last_modified_at: 2021-12-28
---
### 대행사 정산 - *에이전시 정산 조회*
![에이전시정산조회](https://user-images.githubusercontent.com/95394003/147536704-5840df26-98ce-4d60-9919-855427bccf11.jpeg)

#### *구분* <br>
**< 검색 조건 >** **(5)**
<br>에이전시명, 정산번호, 정산일자/지급일, 확정 상태, 지급 상태, 소속 상태

**< 조회 결과 항목 >** **(24)**
<br>No, 체크박스, 정산번호, 정산일, 에이전시명, 확정 상태, 지불 상태,<br> 대상 거래 기간, 매입건수, 매입금액, 매입취소건수, 매입취소금액,<br>합계건수, 수수료액(VAT포함), 차액정산수수료액(VAT포함),<br>정산금액(VAT), 실지급액(VAT 포함), 지급일, 비고, 은행명, 계좌번호,<br>예금주, 대상거래

#### *Description*
- 검색 조건을 입력 및 선택하여 에이전시에 대한 정산 정보를<br>조회합니다.
- 대상거래를 통해 해당 항목에 대한 상세 정보를 엑셀 파일로<br>다운로드할 수 있습니다.
- 정산 기능을 통해 선택한 항목에 대한 지급완료 처리를 할 수 있습니다.
- 은행 지급 데이터를 생성할 수 있습니다.(우리/국민/하나)

#### *Detail*
<br>

![에이전시정산조회검색조건](https://user-images.githubusercontent.com/95394003/147536912-9b369a8f-0907-40a3-ab00-9c516103893f.jpeg)
###### 에이전시명
에이전시명을 입력합니다.

###### 정산번호
정산번호를 입력합니다.

###### 정산일자/지급일
정산일자, 지급일의 조회할 기간을 설정합니다.<br>날짜부터 날짜로 설정 가능합니다.

###### 확정 상태
확정 상태를 선택합니다. 확정, 대기, 지급, 보류로 구분됩니다.

###### 지급 상태
지급 상태를 선택합니다. 대기, 지급대기, 지급완료로 구분됩니다.

###### 소속 선택
지사를 선택합니다.
<br>
<br>

![에이전시정산조회 검색결과](https://user-images.githubusercontent.com/95394003/147536959-9cef2c3d-633a-4293-9fb5-d8f362d593e9.jpeg)
###### No
조회된 결과의 리스트 번호를 나타냅니다.
<br>
<br>

![에이전시 정산기능](https://user-images.githubusercontent.com/95394003/147537101-d1a7d088-6545-40aa-a1f2-b974fafad316.jpeg)
![에이전시은행지급데이터](https://user-images.githubusercontent.com/95394003/147537163-8eaa73e9-e0b2-47d5-be5a-6de7e791f9a2.jpeg)
###### 체크박스
체크박스입니다.<br>각 항목에 체크를 하여 선택항목에 대해 지급완료 처리할 수도,<br>은행 지급 데이터를 생성할 수도 있습니다.

###### 정산번호
정산정보를 나타냅니다.

###### 정산일
정산일이 언제인지를 나타내며 날짜로 표기됩니다.(연,월,일)

###### 에이전시명
에이전시명을 표기합니다.

###### 확정 상태
확정, 대기, 지급, 보류로 상태가 구분됩니다.

###### 지불 상태
대기, 지급대기, 지급완료로 지불 상태가 구분됩니다.

###### 대상 거래 기간
대상 거래 기간이 언제인지를 나타냅니다.<br>
날짜부터 날짜로 표기됩니다.

###### 매입건수
거래 기간에 따른 매입 건수를 나타냅니다.

###### 매입금액
거래 기간에 따른 매입 금액을 나타냅니다.

###### 매입취소건수
거래 기간에 따른 매입 취소 건수를 나타냅니다.

###### 매입취소금액
거래 기간에 따른 매입 취소 금액을 나타냅니다.

###### 합계금액
매입금액에서 매입취소금액을 제한 금액입니다.

###### 수수료액(VAT)포함
수수료액이 얼마인지를 나타냅니다.

###### 차액정산수수료액(VAT포함)
차액정산수수료액이 얼마인지를 나타냅니다.

###### 정산금액(VAT포함)
정산금액이 얼마인지를 나타냅니다.

###### 실지급액(VAT 포함)
에이전시에 실제 지급되는 금액이 얼마인지를 나타냅니다.

###### 지급일
지급일이 언제인지를 나타냅니다.

###### 비고
참고사항이 있을시 표기됩니다.

###### 은행명
계좌에 해당하는 은행명을 나타냅니다.

###### 계좌번호
계좌번호를 나타냅니다.

###### 예금주
계좌의 예금주를 나타냅니다.
<br>

![대상거래엑셀](https://user-images.githubusercontent.com/95394003/146875647-2377d39f-90b4-4f57-a1c1-6c291f48a83f.jpeg)
###### 대상거래
엑셀 파일을 다운받아 기간동안 이루어진 거래들의 상세 내역을<br>확인할 수 있습니다.