# 모두의 쉐어포인트 데모 in Azure
이 페이지는 Azure IaaS 환경에 쉐어포인트 서버 환경을 구축하고자 하는 분들에게 도움이 될 수 있는 내용을 전달하기 위해 만들어 졌습니다.


## 데모환경 요구사항
1. [요구사항](1.Requirements)

## 아키텍쳐 설계
1. [서비스 아키텍쳐](2.Architecture/Architecture_Service.md)
2. [하드웨어 아키텍쳐](2.Architecture/Architecture_Hardware.md)
3. [소프트웨어 아키텍쳐](2.Architecture/Architecture_Software.md)

## 데모환경 구성작업
1. [준비](3.Deployments/1.Preparations.md)
> 1. 준비사항 점검
> 2. 도메인 및 인증서 준비
> 3. Virtual Network 준비
> 4. Azure SQL Database Managed Instance 생성
> 5. Azure Virtual Machine 생성
> 6. AD 도메인 콘트롤러 설치
> 7. AD 도메인 서버 조인

2. [SharePoint Server 설치](3.Deployments/2.Installation.md)
> 1. SharePoint Prerequisites 설치
> 2. SharePoint 미디어 설치
> 3. SharePoint 언어팩 설치
> 4. SharePoint 업데이트 설치
> 5. Office Online Prerequisites 설치
> 6. Office Online 미디어 설치
> 7. Office Online 언어팩 설치
> 8. Office Online 업데이트 설치
> 9. SharePoint & Office Online 서버 인증서 설치

3. [SharePoint Server Farm 구성](3.Deployments/3.Configuration.md)
> 1. Azure SQL Database 권한 부여
> 2. SharePoint 서버 팜 구성
> 3. SharePoint 웹 어플리케이션 생성
> 4. SharePoint 사이트 모음 생성
> 5. Office Online 서버 팜 생성
> 6. Office Online SharePoint 연동
> 7. DNS 서버 등록

4. [(선택) 온프레미스-온라인 사용자 동기화 필요 시](3.Deployments/4.Hybrid.md)
> 1. M365 커스텀 도메인 등록
> 2. 도메인 사용자 UPN 변경 
> 3. Azure AD Connect 미디어 설치
> 9. 하이브리드 구성

5. [웹서버 로드밸런싱 구성](3.Deployments/5.LoadBalancer.md)
> 1. Azure에서 활용할 수 있는 HA 구성
> 2. Azure LoadBalancer 구성

## 데모시연

## 남은일 및 고려사항


## 사용도구
* VSCODE
* mRemoteNG
* https://code.visualstudio.com/blogs/2021/06/10/remote-repositories 
* https://app.diagrams.net/ 
