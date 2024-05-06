# UFO System 명명 규칙

## 레파지토리 명명 규칙 구조
- **소문자 및 하이픈 사용**: 모든 저장소 이름은 소문자로 작성하고 단어 사이에는 하이픈(-)을 사용합니다.
- **서비스-역할-플랫폼** 형식을 따릅니다:
  - **서비스(Service)**: 프로젝트나 서비스의 주요 기능 또는 구성 요소
  - **역할(Role)**: 해당 저장소가 프로젝트 내에서 수행하는 역할
  - **플랫폼(Platform)**: 주로 사용되는 기술이나 개발 언어

## 예시
- **ufo-backend-management-node**
  - **서비스**: ufo-backend
  - **역할**: order-management
  - **플랫폼**: node (Node.js 사용)

- **ufo-frontend-page-react**
  - **서비스**: ufo-frontend
  - **역할**: order-page
  - **플랫폼**: react (React 사용)

- **ufo-frontend-login-management-react**
  - **서비스**: ufo-frontend
  - **역할**: login-management
  - **플랫폼**: react (React 사용)

- **ufo-sms-notification-service**
  - **서비스**: ufo-sms
  - **역할**: notification-service
  - **플랫폼**: (특정 플랫폼 없이 SMS 관련 서비스)

## 저장소 명명 예시
- **ufo-backend-mysql**
  - mysql 사용한 백엔드 주문 관리 시스템

- **ufo-frontend-checkout-react**
  - React를 사용한 프론트엔드 결제 페이지

- **ufo-api-payment-toss**
  - 토스 API를 이용한 결제 처리 API
 
- # 변수 공통 명명 규칙

## 기본 원칙
- 명확하고 이해하기 쉬운 이름을 사용합니다.
- 코드 내에서 일관된 명명 규칙을 유지합니다.
- 축약어는 가능한 피하되, 널리 알려진 축약어는 허용합니다 (예: `info` 대신 `information`).

## 변수 명명 규칙

### 카멜 케이스 (camelCase)
- 변수와 함수 이름은 소문자로 시작하고, 이후 각 단어의 첫 글자는 대문자로 시작합니다.
- 예: `orderCount`, `updateOrderStatus`

### 파스칼 케이스 (PascalCase)
- 클래스와 생성자 함수의 이름에 사용합니다.
- 예: `Order`, `UserProfile`

### 상수
- 상수는 모두 대문자로 작성하고, 단어 사이는 언더스코어(_)로 구분합니다.
- 예: `MAX_SIZE`, `DEFAULT_COLOR`

## 함수 명명 규칙
- 함수 이름은 동사로 시작하며 그 후 명사가 올 수 있습니다. 이는 함수가 수행하는 작업을 명확히 설명해야 합니다.
- 예: `calculateTotal`, `fetchUserData`

## 클래스 명명 규칙
- 클래스 이름은 항상 파스칼 케이스를 사용합니다. 클래스는 명사 또는 명사구를 사용하여 무엇인지를 나타냅니다.
- 예: `Customer`, `HttpResponse`

## 불리언 변수
- 불리언 변수는 종종 ‘is’, ‘can’, ‘has’ 등의 접두사를 사용하여 변수가 불리언임을 나타냅니다.
- 예: `isVisible`, `canSave`, `hasEntries`

## 배열과 컬렉션
- 배열이나 컬렉션은 복수형 이름을 사용하여 여러 값을 포함한다는 것을 나타냅니다.
- 예: `users`, `items`

## 예외 및 특수 경우
- 기술적인 제약이나 외부 라이브러리의 명명 규칙에 의해 영향을 받을 경우, 그 규칙을 따를 수 있습니다.
- 예: DOM API 사용 시 JavaScript 특유의 명명법을 따름.

## 사례 연구
- 좋은 예: `emailAddress`, `saveOrder`, `deleteUser`
- 나쁜 예: `eaddr`, `svordr`, `delusr`
