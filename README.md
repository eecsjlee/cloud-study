# ☁️ Cloud Study

AWS와 Microsoft Azure를 중심으로 클라우드 컴퓨팅에 대해 학습한 내용을 정리한 저장소입니다.

## Contents

### AWS
[AWS 서비스 정리](./aws/aws.md)

### Azure
[Azure 서비스 정리](./azure/azure.md)

# ☁️ Cloud Study

클라우드 컴퓨팅에 대한 학습을 정리하는 저장소입니다.  
이 저장소는 AWS, Microsoft Azure를 중심으로 클라우드 인프라 구성, 서비스 활용, 실습 예제 등을 정리하고 있습니다.

## 📘 클라우드 컴퓨팅이란?

클라우드 컴퓨팅은 **인터넷을 통해 서버, 저장소, 데이터베이스, 네트워크, 소프트웨어 등 IT 리소스를 필요한 만큼 제공**하는 기술입니다.  
사용자는 하드웨어를 직접 구매하거나 설치하지 않아도 원하는 만큼의 컴퓨팅 자원을 즉시 사용할 수 있습니다.

## 🧱 서비스 모델 분류

클라우드 컴퓨팅은 제공 방식에 따라 세 가지 모델로 나뉩니다.

### 1. IaaS (Infrastructure as a Service)
> 가상화된 하드웨어 리소스를 서비스 형태로 제공

- 사용자가 OS, 미들웨어, 애플리케이션 등을 직접 설치 및 관리
- 유연성과 확장성이 높지만 설정과 운영에 대한 부담도 존재
- 예시:  
  - **AWS EC2**  
  - **Azure Virtual Machines**

### 2. PaaS (Platform as a Service)
> 애플리케이션 실행 환경을 서비스 형태로 제공

- 인프라 관리가 필요 없으며, 코드만 업로드하면 애플리케이션이 실행됨
- 배포, 스케일링, 로드밸런싱 등을 플랫폼이 자동으로 처리
- 예시:  
  - **AWS Elastic Beanstalk**  
  - **Azure App Service**

### 3. SaaS (Software as a Service)
> 웹을 통해 소프트웨어를 바로 사용할 수 있는 서비스

- 사용자는 설치 없이 브라우저로 접근
- 공급자가 모든 것을 관리 (인프라 + 애플리케이션)
- 예시:  
  - **Microsoft 365, Gmail, Notion, Slack**

| 분류  | 제공 범위 | 사용자의 역할 | 예시 |
|-------|-----------|----------------|------|
| IaaS  | 서버, 네트워크, 저장소 | OS부터 앱까지 직접 설치 및 관리 | EC2, Azure VM |
| PaaS  | 런타임 환경 + 프레임워크 | 앱 개발 및 배포에 집중 | Elastic Beanstalk, App Service |
| SaaS  | 애플리케이션 완제품 | 사용만 하면 됨 | Gmail, Microsoft 365 |

> 💡 참고: IaaS는 유연하지만 복잡하고, SaaS는 편리하지만 커스터마이징이 제한적입니다.  
> 사용 목적에 따라 적절한 서비스 모델을 선택하는 것이 중요합니다.

## 📚 정리된 내용

- [AWS 서비스 정리](./aws/README.md)
- [Azure 서비스 정리](./azure/README.md)
- [클라우드 용어 정리](./glossary.md)

