# Multi-Hybrid Cloud Project

## 🗓 프로젝트 일정

**2024.06.21 ~ 2024.06.27 (총 7일)**

## 📚 주제

AWS, NHN 클라우드, OpenStack을 활용한 멀티 하이브리드 클라우드 환경 구현

## 📜 요청 상황

기업들이 클라우드 인프라의 안정성과 확장성을 요구함에 따라, 다양한 클라우드 서비스를 통합해 효율적이고 신뢰성 높은 클라우드 환경을 구축하고자 합니다. 특히 비용 절감, 보안 강화, 관리 효율성을 목표로 합니다.

## 🎯 목적과 목표

### 목적

- 여러 클라우드 플랫폼 간의 원활한 연동을 통해 멀티 하이브리드 클라우드 환경을 구축함으로써 시스템의 고가용성, 유연성, 보안성을 높입니다.

### 목표

- **Terraform**을 사용하여 인프라 코드화를 통한 자동화 및 일관성 확보.
- **멀티 클라우드** 아키텍처를 통해 AWS와 NHN 클라우드 간의 데이터 동기화와 네트워크 연동.
- **Private 클라우드**를 구축하여 민감 데이터의 보안성을 강화하고 내부 자원의 유연한 관리 가능.

## 🏗 기술 아키텍처

### 멀티 클라우드 구성

- **AWS 클라우드**: 컴퓨팅 자원 (EC2), 스토리지 (EBS), 네트워크 (VPC), 보안 (IAM, WAF)
- **NHN 클라우드**: 인프라 (IaaS), 스토리지 (S3 호환 오브젝트 스토리지), 네트워크 (VPC)
- **Private 클라우드 (OpenStack)**: 물리적 및 가상화된 서버 관리, 전용 네트워크

### 네트워크 연동

- AWS와 NHN 클라우드 간 **VPN** 연결로 안전한 네트워크 통신 구현.
- 데이터 **DMS**를 사용해 실시간 동기화 및 장애 대처.

## 🚀 주요 기능 & 기술

- **Terraform**: 인프라 코드화를 통해 자동화된 배포 및 관리.
- **OpenStack**: 보안성 높은 Private 클라우드 환경 구축.
- **VPN & DMS**: 클라우드 간 네트워크 연결 및 데이터 동기화.
- **로드 밸런싱 (ALB)**: 트래픽 분산을 통한 안정적인 서비스 제공.
- **이중화 구성**: RDS를 통해 데이터베이스의 고가용성 확보.
- **보안**: IAM 및 WAF를 통해 접근 제어 및 트래픽 보호.

## 📝 성과 및 결과

- **고가용성**: VPN과 DMS를 통해 장애 발생 시에도 서비스 연속성 보장.
- **인프라 코드화**: Terraform을 사용해 인프라를 코드로 관리, 일관성 및 효율성 증대.
- **보안 강화**: Private 클라우드를 통해 데이터 보안을 유지하며 NHN 클라우드와 AWS 클라우드의 보안 기능을 활용.
- **유연성**: 다양한 클라우드 서비스의 통합 관리로 유연한 인프라 확장 가능.

## 📂 산출물

- **보고서**
    - WBS
    - 계획보고서
    - 기술보고서
    - 완료보고서
- **PPT 발표 자료**
- **시방서**

## 👥 역할과 기여

- **김준용**: 프로젝트 관리자, NHN 클라우드 구축 및 Terraform 구성.
- **이도영**: AWS 클라우드 구축 및 보안 설정, 이중화 구성.
- **손은지**: 프로젝트 문서 관리, 멀티 클라우드 연동 계획 수립.
- **최원영**: OpenStack 설정 및 Private 클라우드 구축.

---

## 🔖 성과

<img src="https://github.com/rey265/KINCLOUD/blob/main/KIN-CLOUD-main/image/dns.png">

<br>

<img src="https://github.com/rey265/KINCLOUD/blob/main/KIN-CLOUD-main/image/login%20success.png">

<br>

<img src="https://github.com/rey265/KINCLOUD/blob/main/KIN-CLOUD-main/image/sign-up_success.png">

<br>
# 📝 프로젝트 진행 관리: Notion

### 🔗 URL
https://sonrey.notion.site/Project-Team-Notion-KIN-Cloud-007806073dbf41ad81783f42c4ee5f4d?pvs=4

<br>

<img src="https://github.com/rey265/KINCLOUD/blob/main/KIN-CLOUD-main/image/Project%20Team%20Notion%20KIN%20Cloud%20.png">

<br>


# 📝 발표 PPT:
https://online.fliphtml5.com/viwpp/mwfv/

<br>

<img src="https://github.com/rey265/KINCLOUD/blob/main/KIN-CLOUD-main/image/ppt.jpg">
