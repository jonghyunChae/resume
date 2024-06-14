---
layout: default
---

**※ 해당 문서는 2024년 6월에 작성되었습니다. ※**

* 이름 : 채종현
* 생년 : 1993년생
* 경력 : 2016. 7. ~
1. 능동적이고 개발속도가 빠르며 속도 대비 안정적인 코드를 작성한다는 평가를 받았습니다. 
2. 주어진 업무 외에도 스스로 기존 코드를 개선을 하는 것을 좋아합니다. 
3. 미흡할지라도 기반 아키텍쳐 구축하는 것을 좋아합니다.

<br>
----------------------
# Work Experiences
### 프라시아 전기 (Project ER) / 서버 유닛
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2022. 05 ~ 현재 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( 2년 이상 진행 중 )
##### <br>개발 환경
	 `C# 12` `.NET 8` `RestAPI - Kreskel (ASP.NET Core)`
	 `MSSQL (Sql Server)` `ADO.NET 기반의 Toz Library` `SSDT(sql server data tool)` 
	 `T4 Template` `.NET Code Analysis` `Resharper` `DotMemory` `DotTrace`
	 `JIRA` `Confluence` `Jenkins` `Perforce (p4)` `Swarm(review)`
	 `NLog` `BigQuery` `Snowflake` 
	 Nexon Platform
	  - `NxLog` `Toy` `TozEngine(ADO.Net 기반의 ORM, 직렬화 Framework)` `NxCommand` `GOT` `Submarine`
##### <br>Description.
Seamless 월드 기반의 공성전이 메인인 `MMORPG` 게임입니다.<br>
2023년 3월 31일의 `게임 런칭`에 기여했습니다.<br>
NavMesh 기반의 게임이고 게임 클라이언트 접속이 종료되어도 비접속 중에 게임 플레이를 할 수 있는 어시스트 시스템이 있습니다.<br>
`Monolithic`한 서버 기반에 `비동기 Task 및 TaskSchedular 기반 프로그래밍`을 통해 성능을 최대한 끌어올린 방식의 아키텍처를 사용했습니다.<br>
많은 개발에 참여하다보니 길드, 공성전을 제외하고는 대부분 작업을 해본적이 있지만 크게 담당을 해봤던 기능 위주로 적었습니다.<br><br>

	- **거래소**
	  - 런칭 전 안정화 및 테스트
	  - 부하 테스트, 프로파일링 및 성능 개선
	- **아이템 및 재화**
	  - 기간제
	  - 런칭 전 소모 및 롤백 안정화 구축
	  - 유/무료 재화 및 KPI 로그
	- **캐시샵**
	  - TOY 빌링, WPC 연동 및 KPI 로그
	  - 런칭 전 안정화
	- **비접속 모드(어시스트) 시스템** 
	  - 자동 전투 관련 담당
	  - 어시스트 중 InterServer Migration 관련 로직 개선
    - **인스턴스 필드 범용화**
	  - 인스턴스 던전 기반 시스템 개발
	  - 특수화 되어있던 필드 구성을 모든 시스템을 인스턴스 필드에서 활용할 수 있도록 개선 (마을 기능, 어시스트 등)
	- **그 외 전투, 사망, 버프, 스킬 시스템 개발 등**
<br>
  - ## Nexon Korea
### 마비노기 영웅전 / 서버 유닛
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2018. 05 ~ 2022. 05 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( 4년 )
##### <br>개발 환경
	 `C# (메인)` `.NET Framework 4.8` `C/C++` `Windows Server` 
	 `MSSQL (Sql Server)` `LINQ to SQL` 
	 `Proudnet` `Redis` `소스 엔진 기반의 Dedicated Server`
	 `JIRA` `CCNET` `Perforce (p4)` `AWS`
	 (Nexon Platform) `Arena`
##### <br>Description.
마을에서는 `RPG`, 전투는 방에서 던전을 플레이하는 액션 `MORPG` 게임입니다.<br>
`윈도우 서버`에서 `C#`으로 서버 개발, `C++`로 클라이언트 개발과 `Dedicated Server`를 사용하는 프로젝트 입니다.<br>
마을에서는 일부 `MMO` 방식으로도 작동하며 채널기반의 구조입니다.<br>
MSA는 아니지만 일정 부분 흡사한 Service 기반의 확장성있는 아키텍처를 사용했습니다.<br>
Enumerator를 이용하여 요청을 `corutine` 방식으로 처리하는 아키텍처를 사용했습니다.<br><br>

    - **Multi-Process 재활용**
	  - 기존에 Host 역할을 하는 Multi-Process는 P2P가 끝나면 종료되던 상황
	  - P2P 마다 Multi-Process 생성 비용이 곧 전투 로딩 속도가 되다보니 재활용하도록 보완
	  - 기존 엔진 라이브러리를 수정, Native Socket 처리를 통해 새롭게 Host 역할 처리
	- **아레나 런처 도입 / 패킹 배포 프로세스 변경**
	  - 해외 클라이언트 FTP 업로드 방식에서 아레나 및 스팀 업로드로 변경
	  - 해외 서버 FTP 업로드 방식에서 자동 SVN 업로드로 변경
	- **각종 기능 개선**
	  - 머신 문제로 서비스 끊어진 상황을 판단하기 위한 Keep-Alive 도입
	  - 빈번한 Reflection 처리하던 아키텍처를 Expression Tree로 성능 개선
	  - Roslyn을 이용하여 코드 양식을 잘못 사용을 판단하기 위한 코드규칙 분석기 구축
	  - Retail 환경에서 치트키를 따로 구축하던 환경에서 자동으로 사용할 수 있는 시스템
	  - C++/CLI VS2012에서 VS2019로 Migration  
	  - 그 외 아이템 드랍구조 전면 리팩토링, 전투서비스 로그 개선 등	  
    - **실시간 욕설/광고탐지 필터링, Cash-Out 등 넥슨 API 모듈 도입**
    - **각종 컨텐츠 개발**	  
<br>
  - ## Zepetto
### PointBlank / Server Engineer
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2016. 07 ~ 2018. 05 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( 1년 11개월 )
##### <br>개발 환경
	 `C/C++` `Windows Server` `MSSQL (Sql Server)` `TCP IOCP` `UDP IOCP` `자체 개발 Dedicated Server`
	 `JIRA` `TFS(Team Foundation Server)` `Git` `SVN` 
##### <br>Description.
당시 동남아, 브라질 등에서 국민 FPS로 유명했던 프로젝트이자 첫 경력 프로젝트입니다.<br>
`윈도우 서버`의 `실시간 FPS 서버`, `Dedicated Server` 환경에서 `C/C++`로 `TCP IOCP`와 `UDP IOCP` 기반으로 개발 했습니다. <br>
`Monolithic`한 아키텍처였으며, 확장성 보다는 성능에 중점을 둔 프로젝트 였습니다.<br>
`Multi-Thread` 구조 서버였고, lock 최소화 위한 스레드 역할을 분리한 환경이었습니다.<br>
자체적으로 구축 된 `Dedicated Server` 환경이었으며 개발 및 핵 대응도 함께 했습니다.<br>
높은 동접 환경에서 다양한 트러블 슈팅, 많은 국가들의 전반적인 Live 이슈 대응부터 로그 서버 전담, 전반적인 컨텐츠 및 게임모드 개발 등 다양한 개발을 했습니다.<br><br>

    - **로그서버 관리 및 최적화**
	  - 로그가 많은 서버에는 적재 과정에 상당한 딜레이가 발생하고 있던 상황
	  - 더미 생성 당시 포맷을 변경시켜 BCP에 적합한 포맷으로 변경
	  - Bulk Insert를 통한 Parsing 및 IO 비용을 감축
	  - 로그 서버에 발생하는 전체적인 IO 감소 등을 위해 지속적은 개편/유지 보수를 진행
	  - 기존 자체개발 로그 라이브러리가 thread-safe하지 않아, TLS를 이용하여 개발자가 thread-safe한 편하게 사용할 수 있는 구조로 변경
	  - 그 외 실시간 로그, 로그 포맷 컨버터, 로그 적재 테스트 툴 등 개발
    - **Global Log**
	  - 많은 국가에서 서비스 로그 적재를 한 곳으로 모으는 프로젝트
      -	로그 적재 후에 Post-Processing으로 압축 후, S3에 적재하는 Sender 구축 및 Global Log 환경 구축에 지원
	- **Dedicated Server의 Resource 비동기 로드**
	  - 서버 부팅 시 Resource Load 및 Parsing에서 많은 시간 소요되던 것을 비동기로 시간 대폭 감축
    - **여러 컨텐츠 및 게임모드 개발 및 유지 보수**
	- **대회 서버 구축 지원** 

<br>

----------------------
# Other Experience
<br>
  - ### 학부시절 프로젝트 (2015년)
##### <br>개발 환경
	 `C/C++` `Windows Server` `DirectX 11` `MSSQL (Sql Server)` `IOCP` `Git`
##### <br>Description.
학부시절 졸업 프로젝트로 게임 클라이언트를 개발한 적이 있습니다. (너무 오래되어서 간략하게만 나열)<br>
DirectX 버전 11 기반으로 개발했었으며, Multi-Thread Rendering부터, SIMD, 각종 Shader 처리를 위해 다양한 문서를 참고하여 많은 기술을 해당 프로젝트에 넣어보려고 공을 들였습니다.<br><br>
<br>

----------------------
# Skills
  - ### C / C++
    - 2018년 이전에는 C/C++을 메인으로 클라이언트/서버 개발을 진행
    - 넥슨코리아 입사 후, 2018년 이후 부터는 가끔 클라이언트 개발 지원에 C/C++을 사용하게 됨
	- C++11/14 정도까지는 자주 사용해 봄
<br>
  - ### .NET (C#)
	- .NET Framework 4.8
	- .NET 8 (C# 12)
	- Task 기반 비동기 프로그래밍(TaskSchedular, Async/Await 등)
	- Windows form
	- Linq To Sql, ADO.Net 기반의 TozORM
	- Expression Tree, Roslyn
<br>
  - ### Python
    - 학부 시절에 SDL Lib와 함께 2D 게임 개발에 사용
	- 현업에서는 단순한 Tool 정도 개발에만 사용
	- 그 외는 개인 공부 목적으로 경험해본 정도
<br>
  - ### Network & Server Programming
    - Socket Programming 
    - TCP/UDP IOCP 개발
	- Windows Server
	- P2P (Hole Punching) & Dedicated Server
    - Http API 연동을 위한 개발 정도
<br>
  - ### Database
    - MSSQL
	- SSDT (Sql Server Data Tool)을 통한 dacpac기반 Database 관리
<br>
  - ### DirectX 11
    - 학부시절 HLSL, Depth-Stencil, Pipeline, Multi-Thread Rendering, Blur, HDR 등 경험
<br>

---------------------
# Education

  - ### 학사 (4년제)
    - ##### 한국산업기술대학교 게임공학과
###### 2011. 03 ~ 2017. 02 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  
---------------------

