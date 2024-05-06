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
