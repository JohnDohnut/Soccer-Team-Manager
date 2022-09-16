# SoccerTeamManagementSystem

## Purpose
~~~
  - 축구팀 구성원의 정보관리 시스템 개발
  - DB연동과 WAS를 통한 환경 구축
~~~


## Function
### 선수/팀/감독 별 정보 관리
~~~
  1. 사용자는 선수/팀/감독별로 분류된다.
  2. 각 사용자에게는 권한이 부여되고 그 권한내에서만 정보를 삭제/수정/생성할 수 있으며, 권한 밖의 정보는 조회만 할 수 있다.
  3. 각 선수는 자신의 경기 정보를 관리한다.
  4. 각 감독은 자신이 속한 팀을 관리한다.
  5. 각 팀은 자신에게 속한 선수를 관리한다.
  
~~~
### 상세
~~~
  
  1. 선수의 정보에는 선수의 정보(선수의 이름, 선수의 고유번호 등), 소속된 팀과 선수의 경기 기록들이 기록된다.
  2. 팀의 정보에는 팀의 정보(팀의 이름, 팀의 고유번호 등), 선수와 선수의 포지션이 기록된다.
  3. 감독의 정보에는 감독의 정보(감독의 이름, 감독의 고유 번호 등)와 관리중인 팀들이 기록된다.
  4. 선수의 경기 기록은 선수의 팀, 상대 팀, 기록의 형태 로 나뉜다.
~~~

### 계정 관리
~~~
  1. 모든 선수는 오로지 한 팀에만 종속될 수 있다.
  2. 감독은 여러 팀을 관리할 수 있다.
~~~


## Tech
~~~
Apache Tomcat
Spring boot
MySQL
~~~
##Flow
~~~
![화면 캡처 2022-09-16 125853](https://user-images.githubusercontent.com/51821505/190553707-a85391c1-f276-48bf-99c3-ceea85a738eb.png)

~~~
##DB Schema
