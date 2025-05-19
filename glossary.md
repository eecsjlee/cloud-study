# 클라우드 용어 정리

## 클라우드 기본 용어

* **Multi-Cloud**
  둘 이상의 클라우드 제공자(AWS, Azure, GCP 등)를 동시에 사용하는 전략. 공급자 종속을 피하고 고가용성을 확보할 수 있음.

* **Hybrid Cloud**
  퍼블릭 클라우드와 프라이빗 클라우드를 혼합하여 사용하는 구조. 기업 내부 시스템과 외부 클라우드를 연동.

* **Edge Computing**
  클라우드와 사용자 사이에 위치한 장치에서 데이터를 처리하여 지연 시간과 네트워크 부담을 줄이는 방식.

## 서비스 모델

* **BaaS (Backend as a Service)**
  인증, 데이터 저장, 푸시 알림 등 백엔드 기능을 API 형태로 제공하는 서비스. 예: Firebase, AWS Amplify.

## 보안 및 접근 제어

* **RBAC (Role-Based Access Control)**
  역할 기반 접근 제어. 사용자에게 권한이 아닌 역할을 부여하고, 역할에 따라 권한을 할당하는 방식.

* **Least Privilege Principle**
  최소 권한 원칙. 사용자나 애플리케이션에 필요한 최소한의 권한만 부여하는 보안 전략.

## 스토리지

* **Cold Storage**
  장기 보관용 저비용 스토리지. 접근 빈도가 낮은 데이터를 위한 저장소. 예: S3 Glacier, Azure Archive.

* **Lifecycle Policy**
  데이터의 저장 기간에 따라 자동으로 스토리지 클래스를 전환하거나 삭제하는 규칙.

## DevOps / 운영

* **Blue/Green Deployment**
  기존 서비스(Blue)와 새 버전(Green)을 동시에 운영하여 트래픽을 전환하는 방식. 롤백이 쉬움.

* **Canary Deployment**
  새 버전을 일부 사용자에게만 먼저 배포하고 이상이 없으면 전체로 확장하는 방식.

* **Observability**
  로그, 메트릭, 트레이스를 통해 시스템 상태를 파악하고 문제를 진단하는 능력. 모니터링보다 넓은 개념.
