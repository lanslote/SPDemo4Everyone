# 하드웨어&소프트웨어 아키텍쳐

## 하드웨어 요구사항
https://docs.microsoft.com/en-us/sharepoint/install/hardware-and-topology-requirements-for-sharepoint-server-subscription-editon

## 소프트웨어 요구사항
https://docs.microsoft.com/en-us/sharepoint/install/software-requirements-for-database-servers-for-sharepoint-server-subscription-edition

## 데이터베이스 요구사항
https://docs.microsoft.com/en-us/sharepoint/install/software-requirements-for-database-servers-for-sharepoint-server-subscription-edition

## Office Online 요구사항
https://docs.microsoft.com/en-us/officeonlineserver/plan-office-online-server#:~:text=You%20can%20run%20Office%20Online,2021%20patch%20or%20later%20required).

## 그외 고려사항
인터넷 아웃바운드 연결을 권장합니다. 그것이 불가능할 때에는...
- 설치시에 Prerequisite (사전설치구성요소)를 미리 다운로드하여 수동설치 해야 합니다.
- CRL(Certificate Revocation List) 접속을 하지 못하는 것때문에 응답속도가 지연되는 현상이 발생하므로 그에 대비한 조치가 필요합니다.
- [Site slowness because of SharePoint STS certificate CRL checking](https://docs.microsoft.com/en-us/sharepoint/troubleshoot/sites/site-slowness-because-of-sts-certificate-crl-checking)
