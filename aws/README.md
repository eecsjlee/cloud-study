# ☁️ AWS 서비스 정리

Amazon Web Services(AWS)의 주요 서비스들을 분류별로 정리한 문서입니다.  
클라우드 인프라 구축, 백엔드 개발, 데이터 관리 등 다양한 분야에서 사용되는 서비스들을 공부하며 정리합니다.

## 📦 컴퓨팅 (Compute)
| 서비스 | 설명 |
|--------|------|
| **EC2 (Elastic Compute Cloud)** | 가상 서버 인스턴스를 제공하는 핵심 서비스 |
| **Lambda** | 서버 없이 코드를 실행할 수 있는 FaaS(Function as a Service) |
| **Elastic Beanstalk** | 애플리케이션을 빠르게 배포할 수 있는 PaaS 서비스 |
| **ECS (Elastic Container Service)** | 컨테이너 오케스트레이션 서비스 |
| **EKS (Elastic Kubernetes Service)** | Kubernetes 기반의 컨테이너 관리 서비스 |

## 🗂️ 스토리지 (Storage)
| 서비스 | 설명 |
|--------|------|
| **S3 (Simple Storage Service)** | 객체 기반의 파일 저장소 |
| **EBS (Elastic Block Store)** | EC2에 연결하는 블록 스토리지 |
| **EFS (Elastic File System)** | NFS 기반의 공유 파일 시스템 |

## 🛡️ 보안 및 접근 제어 (Security & IAM)
| 서비스 | 설명 |
|--------|------|
| **IAM (Identity and Access Management)** | 사용자 및 권한 제어 |
| **KMS (Key Management Service)** | 암호화 키 관리 |
| **Cognito** | 사용자 인증 및 소셜 로그인 지원 |

## 🌐 네트워킹 (Networking)
| 서비스 | 설명 |
|--------|------|
| **VPC (Virtual Private Cloud)** | 가상 네트워크 구성 |
| **Route 53** | DNS 및 도메인 라우팅 서비스 |
| **API Gateway** | REST API 및 WebSocket API 게이트웨이 제공 |
| **CloudFront** | CDN(Content Delivery Network) 서비스 |

## 🛠️ 개발 및 운영 도구 (DevOps & Monitoring)
| 서비스 | 설명 |
|--------|------|
| **CloudWatch** | 로그 및 모니터링 서비스 |
| **CloudTrail** | API 호출 기록 추적 서비스 |
| **CodeCommit** | Git 기반의 소스 코드 저장소 |
| **CodeBuild** | 자동 빌드 서비스 |
| **CodeDeploy** | 배포 자동화 서비스 |
| **CodePipeline** | CI/CD 파이프라인 구축 도구 |

## 🗃️ 데이터베이스 (Database)
| 서비스 | 설명 |
|--------|------|
| **RDS (Relational Database Service)** | MySQL, PostgreSQL, MariaDB 등 관리형 관계형 DB |
| **DynamoDB** | 완전관리형 NoSQL 데이터베이스 |
| **Aurora** | 고성능 관계형 DB (MySQL/PostgreSQL 호환) |
| **ElastiCache** | Redis/Memcached 기반의 인메모리 캐시 |

## 🧠 AI/ML 서비스 (AI & Machine Learning)
| 서비스 | 설명 |
|--------|------|
| **SageMaker** | 머신러닝 모델 학습, 배포 서비스 |
| **Rekognition** | 이미지/영상 인식 서비스 |
| **Comprehend** | 자연어 처리(NLP) 서비스 |
| **Lex** | 챗봇 개발 서비스 (Alexa 기술 기반) |
| **Polly** | 텍스트 음성 변환(TTS) 서비스 |

## 📊 분석 및 빅데이터 (Analytics & Big Data)
| 서비스 | 설명 |
|--------|------|
| **Athena** | S3 데이터를 SQL로 분석하는 서비스 |
| **Redshift** | 데이터 웨어하우징 서비스 |
| **Kinesis** | 스트리밍 데이터 처리 서비스 |
| **Glue** | ETL(추출-변환-적재) 자동화 서비스 |

## 📌 기타 유용한 서비스
| 서비스 | 설명 |
|--------|------|
| **CloudFormation** | 인프라를 코드로 정의하는 IaC 도구 |
| **Elastic Transcoder** | 미디어 파일 인코딩 |
| **Step Functions** | 서버리스 워크플로우 오케스트레이션 |
| **SNS / SQS** | 메시징 및 알림 서비스 |

