# 요구사항
이 데모환경을 구축하기 위한 요구사항 들을 정리해 보겠습니다.

## Environment 
* Azure 인프라 환경을 사용한다.
* Azure VM
* Azure SQL Managed Instance
* Azure Load Balancer

## Domain & Certificate
* 액티브 디렉토리 도메인을 구성한다.
* 인터넷 도메인을 사용하여 외부 인터넷에서 접속할 수 있도록 구성한다.
* 서드파티 인증서를 사용하여 HTTPS 서비스를 구성한다.

## SharePoint
* SharePoint Server SE 버전을 설치한다.
* SharePoint 웹사이트는 L4 이중화를 구성한다.
* SharePoint 웹사이트는 인터넷 주소로 외부에서 접속할 수 있다.
* SharePoint 웹사이트는 서드파티 인증서로 HTTPS 서비스를 한다.
* 필요한 쉐어포인트 서버 기능은 아래에 나열한다.
    * 웹사이트
    * 검색
    * 메일알림
* Office Online Server를 이용해 웹오피스 구성을 제공한다

## SQL
* SQL 서버는 Azure SQL managed Instance를 사용한다.

## Office 365
* Office 365와의 연동기능이 있으면 좋겠다.
* AADC 서버로 계정 동기화 구성한다.
* 사용자들은 Exchange Online 사서함에서 알림메일을 수신한다.
* SharePoint Hybrid 구성을 한다.

    





