**※ 해당 문서는 2022년 3월에 작성되었습니다. ※**

* 이름 : 채종현
* 생년 : 1993년생
* 경력 : 2016. 7. ~
1. 개발속도가 빠르다는 평가를 받았으며, 속도 대비 안정적인 코드를 작성합니다. 
2. 주어진 업무 외에도 여유가 있으면 지속적으로 스스로 개선을 하는 것을 좋아합니다. 
3. 미흡하지만 아키텍쳐 구축하는 것을 좋아합니다.
4. 많은 발전이 필요하지만 메인으로 다루는 분야는 깊게 공부하는걸 좋아합니다.
5. 그 외 개발 분야는 얕게라도 배워서 분야를 넓히려고 노력하고 있습니다.
6. 최근에는 다양한 개발에 관심이 있어서 지속적으로 다양한 분야를 공부하려고 노력하는 편입니다. 
7. 지속적으로 공부하거나 기존 기술에 분석을하면서 나름대로 정리를 하며 필요한 경우에는 팀원들에게 공유하는 습관이 있습니다.

<br>
----------------------
# Work Experiences
<br>
  - ## Nexon Korea
### 마비노기 영웅전 / 서버 유닛
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2018. 05 ~ 현재 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( 3년 11개월 )
##### <br>개발 환경
	 `C# (메인)` `.NET Framework` `C/C++` `Windows Server` `MSSQL (Sql Server)` `Proudnet` `Redis` `Dedicated Server`
	 `JIRA` `CCNET` `Perforce (p4)` `AWS`
##### <br>Description.
가나다라마바사아자차<br><br>

    - **개발내용1**

<br><br>
  - ## Zepetto
### PointBlank / Server Engineer
###### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2016. 07 ~ 2018. 05 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( 1년 11개월 )
##### <br>개발 환경
	 `C/C++` `Windows Server` `MSSQL (Sql Server)` `TCP IOCP` `UDP IOCP``Dedicated Server`
	 `JIRA` `TFS(Team Foundation Server)` `Git` `SVN` 
##### <br>Description.
당시 동남아, 브라질 등에서 국민 FPS로 유명하던 프로젝트이자 저의 첫 경력을 갖게 해준 프로젝트입니다.<br>
`윈도우 서버`의 `실시간 FPS 서버`, `Dedicated Server` 환경에서 `C/C++`로 `TCP IOCP`와 `UDP IOCP` 기반으로 개발 했습니다. <br>
높은 동접 환경에서 다양한 트러블 슈팅, 많은 국가들의 전반적인 Live 이슈 대응부터 로그 서버 전담, 전반적인 컨텐츠 및 게임모드 개발 등 다양한 개발을 했습니다.<br><br>

    - **로그서버 관리 및 최적화**
	  - 로그가 많은 서버에는 적재 과정에 상당한 딜레이가 발생하고 있던 상황
	  - 더미 생성 당시 포맷을 변경시켜 BCP에 적합한 포맷으로 변경
	  - Bulk Insert를 통한 파싱과 IO 비용을 감축
	  - 로그 서버에 발생하는 전체적인 IO 감소 등을 위해 지속적은 개편/유지 보수를 진행
	  - 그 외 실시간 로그, 로그 포맷 컨버터, 로그 적재 테스트 툴 등 개발
    - **Global Log**
	  - 많은 국가에서 서비스 로그 적재를 한 곳으로 모으는 프로젝트
      -	로그 적재 후에 Post-Processing으로 압축 후, S3에 적재하는 Sender 구축 및 Global Log 환경 구축에 지원
	- **Log file Thread-safe**
	  - 기존 자체 로그 라이브러리가 multi-thread에서 safe하지 않은 상황
	  - TLS를 이용하여 개발자가 thread 신경 안쓰고 편하게 사용할 수 있는 구조로 변경
	- **Dedicated Server의 Resource 비동기 로드**
	  - 서버 부팅 시 Resource Load 및 Parsing에서 많은 시간 소요되던 것을 비동기로 시간 대폭 감축
    - **여러 컨텐츠 및 게임모드 개발 및 유지 보수**
	- **대회 서버 구축 지원** 
	- **각 Live 이슈 대응**

<br>

----------------------
# Other Experience
<br>
  - ### 학부시절 프로젝트 (2015년)
##### <br>개발 환경
	 `C/C++` `Windows Server` `DirectX 11` `MSSQL (Sql Server)` `IOCP` `Git`
##### <br>Description.
학부시절 많은 프로젝트 중, 제 클라이언트 경험을 잘 담을 수 있는 프로젝트를 적어 봤습니다.<br>
최대 4인이서 서로 주어진 환경에서 자원을 획득하며 서로 전투하는 방식의 게임 입니다.<br>
해당 프로젝트는 친구가 서버를 맡았고, 저는 클라이언트를 도맡아했습니다. <br>
DirectX 버전 11 기반으로 개발했었으며, Multi-Thread Rendering부터, SIMD, 각종 Shader 기법 문서를 참고하여 많은 기술을 해당 프로젝트에 넣어보려고 공을 들였습니다.<br><br>
![Image1](https://github.com/jonghyunChae/image_upload/blob/main/%ED%81%B4%EB%9D%BC2.png?raw=true)
![Image2](https://github.com/jonghyunChae/image_upload/blob/main/%ED%81%B4%EB%9D%BC1.png?raw=true)
<br>

----------------------
# Skills
  - ### C / C++
    - 2018년 이전에는 C/C++을 메인으로 클라이언트/서버 개발을 진행
    - 넥슨코리아 입사 후, 2018년 이후 부터는 클라이언트 개발에만 C/C++을 사용하게 됨
	- C++11/14 정도까지는 자주 사용해 봄
<br>
  - ### C#
    - 2018년 이전에는 툴 정도에서만 C++ 방식으로 사용
	- 2018년 이후부터는 서버 개발의 메인 언어로 사용
	- Linq 및 Linq To Sql, Expression Tree, Roslyn, Task, Async/Await 등
<br>
  - ### Python
    - 학부 시절에 SDL Lib와 함께 2D 게임 개발에 사용
	- 현업에서는 단순한 Tool 정도 개발에만 사용
	- 그 외는 개인 공부 목적으로 AWS Lambda, Spark 등에서 사용해본 정도
<br>
  - ### Network & Server Programming
    - TCP/UDP IOCP 개발
	- Windows Server
	- P2P (Hole Punching) & Dedicated Server
<br>
  - ### Database
    - MSSQL
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

