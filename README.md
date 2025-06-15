# 스마트팜 농장관리 시스템
## 2024 임베디드 소프트웨어 경진대회

팀 정보 및 프로젝트 관리는 [여기](https://github.com/WebOS-TEAM-DEVMONSTER)에서 확인해주세요


![Image](https://github.com/user-attachments/assets/9196e541-179f-4573-a78f-cb38639fb396)


## 개요

---

스마트팜 및 사용자 관리 프로그램

### 기능

- 사용자는 자신의 농장의 상태를 실시간으로 조회할 수 있습니다.
- 수확량 예측 모델을 기반으로 현재 환경이 식물 재배에 적합한지 평가합니다.
- 농작물 질병 감지 모델을 기반으로 식물에게 병이 있을경우 사용자에게 어떤 병인지 알려줍니다.

## 결과물

---


### 주요 화면

![Image](https://github.com/user-attachments/assets/fa5e3f2b-7012-463e-826d-faaa321e5476)

![Image](https://github.com/user-attachments/assets/00ccdec7-6f72-4fd2-b290-8f1266070d9f)


## 아키텍쳐

---

![Image](https://github.com/user-attachments/assets/39be4eae-a30e-425e-a7b4-dfc9b1d0449b)


## 개발 정보

---


### 개발 기간

- 2024.07 ~ 2024.10


### 개발 인원

- 5명
    - 프론트엔드 2명
    - 센서 조립 1명
    - 백엔드  및 센서정보 전달 1명
    - 농장상태 추론 모델개발 1명


### 핵심 기능

- JWT 기반 회원가입 및 로그인 기능
- 스마트팜 내부 온습도, 토양상태, 식물상태 모니터링
- 온습도, 토양상태, 식물상태를 기반으로 현재 농장의 운영상태 평가


### 지원자 개인 기여

- 서버 개발 및 배포
    - JWT 기반 로그인 및 회원가입
    - 사용자 정보 및 농장정보 관리
    

- 센서 정보 전달
    - 사용자 기기에 실시간으로 농장 센서 정보 표시 및 업데이트
    - 센서 정보를 사용자 농장 데이터베이스에 전달 및 저장
    - 센서 정보를 농장 상태 추론 서버에 전달 및 결과 반환
    

### 사용 기술

- 앱 / 보드
    - RaspberryPi4/WebOS
    - React
    
- 서버
    - Java
    - SpringFramework
    
- 관리 / 배포
    - github
    

- 배포
    - aws ec2 t2.micro
    - nginx
    - docker
    
- DB
    - MongoDB
