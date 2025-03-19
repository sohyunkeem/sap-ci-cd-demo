# sap-ci-cd-demo
SAP CI/CD 구축

# SAP ABAP CI/CD Demo 

SAP ABAP 프로그램을 GitLab CI/CD 파이프라인으로 관리
CI/CD 자동화는 개발 → 테스트 → 배포 과정을 효율적으로 처리

## 프로젝트 구성
- **abap/ZDEMO_PROGRAM.abap**  
  → 간단한 ABAP 테스트 프로그램

- **.gitlab-ci.yml**  
  → GitLab CI/CD 파이프라인 정의 파일  
    - Syntax Check
    - Transport 단계
    - QA 배포 단계로 구성

## 주요 기술
- GitLab CI/CD
- ABAP 코드 버전관리
- SAP 코드 배포 자동화 개념

## 참고
- abaplint, abapGit, SAP CLI 등 추가 도구 설정이 필요
