# TEST·샘플코드

[샌드박스 TEST](../common/test.md#샌드박스test) | [샌드박스 활용](../common/test.md#샌드박스-활용) | [웹로드 디버깅](../common/test.md#웹로그-디버깅) | [샘플코드](../common/test.md#샘플코드) | [더 알아보기](#더-알아보기)

<br>

## 샌드박스(TEST)
### 샌드박스 준비  
[회원가입](/common/preparations.md#회원가입)을 하면 하나의 샌드박스(🔧 TEST 상점)을 생성 할 수 있습니다.  

#### 샌드박스(테스트상점) 생성
- 회원가입 후 로그인 하면 ‘테스트 상점 개설하기‘ 버튼이 활성화 됩니다.
- 버튼 클릭 후 TEST상점 이름을 입력하면 준비가 완료 됩니다.

![image](https://user-images.githubusercontent.com/86043374/128303655-26060514-b86c-4b15-a58d-f6eded03fa08.png)  
로그인 -> 테스트상점 개설하기 -> 정보입력 -> 생성  

#### 샌드박스(테스트상점) TEST
샌드박스(테스트상점)으로 이동 후 개발정보 탭으로 이동하면 개발에 필요한 🔑 키값 확인이 가능하며 즉시 개발을 진행 할 수 있습니다.  
![image](https://user-images.githubusercontent.com/86043374/128303979-6244f466-43f9-4473-a93e-c7cd97748564.png)  
 TEST 상점 선택 -> 개발정보 이동  

<br>

### 샌드박스 활용
회원가입을 하게되면 하나의 샌드박스(TEST 상점)을 생성 할 수 있습니다.  
생성된 샌드박스 상점을 통해 신규 서비스의 TEST 및 개발을 즉시 진행 할 수 있습니다.  
또한 샌드박스 시스템은 개발과 TEST의 번거로움을 줄이기 위해 다양한 장점과 기능을 제공합니다.  

#### 샌드박스 장점
- 즉시 TEST 및 개발이 가능 합니다.
- 결제가 발생되지 않아 편하게 TEST가 가능 합니다.
- 웹 로그를 통해 API 요청/응답 디버깅이 편리 합니다.
- 운영 환경에 영향이 없는 TEST시스템을 구성 할 수 있습니다.
 
#### 샌드박스의 기능
- TEST 결제 및 API 호출 : 상점 전용 TEST계정
- [웹훅 TEST하기](/management/admin.md#test호출) : 원클릭 🔔 웹훅 TEST
- TEST 결과 리포팅 : 운영 시스템 전환 전 간략하게 TEST정보를 요약

   
> 샌드박스 키와 운영상점에서 제공되는 키는 다르며, 실제 운영상점의 결제를 원하는 경우 해당 상점 KEY로 반드시 변경 해주세요.  
> 샌드박스 상점의 API 응답 전문은 실제 결제의 응답이 아닙니다.   
> 운영상점의 KEY로 서비스를 오픈 하는 경우 반드시 실제 거래를 통한 TEST를 진행 해주세요.

<br>

### 웹로그 디버깅
간편한 디버깅을 위해 호출된 API 요청/응답 정보 💿 로그는 웹을 통해 확인이 가능합니다.  
로그는 단순한 호출 기록과, 상세기록을 나누어 확인 할 수 있습니다.  
API요청이 실패하는 경우 상세로그를 확인하여 쉽게 디버깅 해보세요.  

#### 단순 로그 확인
![image](https://user-images.githubusercontent.com/86043374/128304508-9be97076-2fec-474b-85d9-bcfc30b8045d.png)  
개발정보 -> 로그

- API 호출에 대한 성공 / 실패 정보의 빠른 확인이 가능합니다.
- API Target 요약 정보 확인이 편리 합니다.
- 주문번호 확인을 통해 이슈 거래 건 체크가 가능 합니다.

  
#### 상세 로그 확인
![image](https://user-images.githubusercontent.com/86043374/128304865-b0ba8f4a-adf7-45e7-b78a-53b0e01106fc.png)  

- 로그를 확인 중 상세한 정보 확인이 필요한 경우 해당 로그를 클릭하면 상세한 정보 확인이 가능합니다.
- 이슈 체크를 위해 로그 검토가 필요한 경우 ‘상세보기’ 버튼을 클릭하면 상세 로그 화면으로 이동 합니다.
- 로그 상세보기를 통해 디버깅에 필요한 상세 정보를 확인 할 수 있습니다.
  
#### 개발정보
- [개발정보 활용](/management/admin.md#활용)
- [로그-기능설명](/management/admin.md#기능설명-3)
- [로그-상세보기](/management/admin.md#상세보기)

<br>

## 샘플코드	
나이스페이는 개발편의를 위해 다양한 언어의 샘플코드를 제공하고 있습니다.  
[Github](https://github.com/nicepayments/sample)에서 샘플코드를 확인 해주세요.  

### 지원되는 언어
<div align="left"> 
 <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"> 
 <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
 <img src="https://img.shields.io/badge/ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white">
 <img src="https://img.shields.io/badge/asp-007396?style=for-the-badge&logo=&logoColor=white">
 <img src="https://img.shields.io/badge/java-F7DF1E?style=for-the-badge&logo=&logoColor=white">
 <img src="https://img.shields.io/badge/php-777BB4?style=for-the-badge&logo=php&logoColor=white">
 <img src="https://img.shields.io/badge/.net-512BD4?style=for-the-badge&logo=.net&logoColor=white">
</div>

<br>

    
## 더 알아보기
결제 개발을 위해 더 상세한 정보가 필요하다면📌 `공통` 탭의 정보를 활용하고,  
API 개발을 위한 각 인터페이스의 개발 명세가 필요하다면 📚 `문서` 탭의 자료를 확인 해주세요.  
개발이 완료되어 운영에 필요한 정보와 Tip은 ☸️ `운영` 탭의 정보를 통해 확인이 가능 합니다. 

### 📌 공통
개발 전 필요한 `공통`적인 가이드 입니다.  
- [개발 준비](/common/preparations.md) 👉 [회원가입](/common/preparations.md#회원가입) | [API KEY확인](/common/preparations.md#api-key-확인) | [방화벽 정책](common/preparations.md#방화벽-정책) | [IP 보안기능](/common/preparations.md#ip-보안-기능) | [타임아웃 정보](/common/preparations.md#타임아웃-정보)
- [API·JS SDK](/common/api.md) 👉 [URI 목록](/common/api.md#uri-목록) | [JS SDK목록](/common/api.md#js-sdk-목록) | [API KEY](/common/api.md#api-key) | [API·JS SDK인증](/common/api.md#apijs-sdk인증) | [Basic auth](/common/api.md#basic-auth) | [Bearer token](/common/api.md#bearer-token)
- [TEST·샘플코드](/common/test.md) 👉 [샌드박스 TEST](/common/test.md#샌드박스test) | [샌드박스 활용](/common/test.md#샌드박스-활용) | [웹로그 디버깅](/common/test.md#웹로그-디버깅) | [샘플코드](/common/test.md#샘플코드)
- [코드집](/common/code.md) 👉 [HTTP-상태코드](/common/code.md#http-상태코드) | [카드코드](/common/code.md#카드코드) | [은행코드](/common/code.md#은행코드) | [JS SDK 응답코드](/common/code.md#js-sdk-응답코드) | [API 응답코드](/common/code.md#api-응답코드)
  
### 📚 문서
`API 명세`와 `코드`가 포함된 기술문서 입니다.  
- [결제·발급](/api/payment.md#) 👉 [결제창](/api/payment-window-server.md) | [빌링](/api/payment-subscribe.md) | [현금영수증](/api/payment-receipt.md) | [Access token](/api/payment-access-token.md)
- [조회](/api/status.md) 👉 [거래 조회](/api/status-transaction.md) | [약관 조회](/api/status-terms.md) | [카드 이벤트 조회](/api/status-event.md) | [카드 무이자 조회](/api/status-interest.md)
- [거래·정산·대사](/api/reconciliation.md) 👉 [거래대사](/api/reconciliation.md#거래대사) | [정산대사](/api/reconciliation.md#정산대사) | [입금대사](/api/reconciliation.md#입금대사)
- [취소·환불·망취소](/api/cancel.md) 👉  [취소·환불](/api/cancel.md#취소환불) | [망 취소](/api/cancel.md#망취소)
- [웹훅](/api/hook.md) 👉 [웹훅](/api/hook.md#웹훅)
- [APP](/api/app.md) 👉 [iOS](/api/app-ios.md#ios) | [iOS Swift](/api/app-ios.md#ios-swift-웹뷰web-view개발-가이드) | [iOS Objective-c](/api/app-ios.md#ios-objective-c-웹뷰web-view개발-가이드) | [Android](/api/app-android.md#) | [Android java](/api/app-android.md#android-java-웹뷰web-view개발-가이드) | [Android kotlin](/api/app-android.md#android-kotlin-웹뷰web-view개발-가이드)

### ☸️ 운영
`운영`에 필요한 정보 입니다.  
- [지원환경](/management/user.md) 👉 [개발환경](/management/user.md#개발환경) | [지원 브라우저](/management/user.md#브라우저)
- [오류관리](/management/user.md#오류관리) 👉 [오류관리](/management/user.md#오류관리)
- [개발정보](/management/admin.md) 👉 [기능 요약](/management/admin.md#기능-요약) | [KEY 정보](/management/admin.md#key정보) | [ip보안(ip접근제한)](/management/admin.md#ip보안ip접근-제한) | [웹훅](/management/admin.md#웹훅) | [로그](/management/admin.md#로그)
