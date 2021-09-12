# 범죄, 멈춰!

## 1. 프로젝트 소개


본 프로젝트에서는 폭행 상황을 감지하면 현장에 경고음을 출력하고 관리자에게 메일을 전송하는 지능형 cctv 시스템을 구축하고자 한다. 행동 인식(action recognition)을 하는 AI 기술로 CCTV 영상을 분석하여 폭행 발생 여부를 판단한다. 폭행 상황으로 감지된 결과는 CCTV 관리자에게 전송하여 관리자가 위험 상황을 신속하게 대응하도록 보조 할 수 있다. 또한, CCTV의 스피커가 "범죄 멈춰" 음성을 출력함으로써, CCTV 설치 장소에서의 폭력 발생을 예방하는 효과도 기대된다.


<br/>

## 2. Abstract


This project aims to implement a CCTV system that can detect assault immediately. If assault detected, it makes an audio-"Stop Crime!"- and sends an email to a CCTV manager.  It determines whether there happened the situation by using an AI model, which recognizes several human actions. By sending the detected results to CCTV mangers, we hopefully expect the system to assist him or her to deal with the situation quickly and help to prevent attacks by making the audio.
<br/>



#### 중간 발표 영상

[![23조 중간 발표 영상](http://img.youtube.com/vi/mTJcfbAd-b8/0.jpg)](https://youtu.be/mTJcfbAd-b8?t=0s)

#### 시연 동영상

[![23조 시연 영상](http://img.youtube.com/vi/Wo_nVTp51OM/0.jpg)](https://youtu.be/Wo_nVTp51OM?t=0s)
<br/>
#### Slowfast
##### abnormal

https://user-images.githubusercontent.com/54228425/119828068-c76dd280-bf34-11eb-81d9-76145975be8e.mp4
##### normal

https://user-images.githubusercontent.com/54228425/119828130-d8b6df00-bf34-11eb-824e-f5133405bac6.mp4



## 4. 팀 소개


<img align=left src = "https://user-images.githubusercontent.com/21096675/112747542-12c93a80-8ff1-11eb-85e9-965e0c9e78d5.png" width="200px" height="180px">

```markdown
😁 Name : 박건희(팀장)
👨🏻‍💻 ID   : 20163107
📧 Email: pgh9801@kookmin.ac.kr

🛠 Role:
    - Web Application Server, Backend
    - 데이터셋 자동 다운로더 구현

```

<img align=left src = "https://user-images.githubusercontent.com/21096675/113386677-b5086a00-93c5-11eb-8388-1901400ac829.png" width="200px" height="180px">

```markdown
😁 Name : 김소망
👨🏻‍💻 ID   : 20163094
📧 Email: akfls745@kookmin.ac.kr

🛠 Role :
    - 보드 총괄
    - Object Detection
     
```
<img align=left src ="https://user-images.githubusercontent.com/21096675/112747550-178dee80-8ff1-11eb-9eb7-8059c506133e.png" width="200px" height="180px">

```markdown
😁 Name : 임태현
👨🏻‍💻 ID   : 20163153
📧 Email: plmoknijb15@kookmin.ac.kr

🛠 Role :
    - 데이터 셋 구축 & 모델 학습
    - 알림 기능 &  Action classification 모델(slowFast) 성능 향상

```

<img align=left src = "https://user-images.githubusercontent.com/21096675/113386691-bafe4b00-93c5-11eb-98d9-9e3933ae8d1c.png" width="200px" height="180px">

```markdown
😁 Name : 함윤석
👨🏻‍💻 ID   : 20163175
📧 Email: ham5312@kookmin.ac.kr 

🛠 Role :
    - 데이터 셋 구축 & 모델 학습
    - Ai Server 제작 & Action classification 모델(slowFast) 성능 향상

```

<br/>

## 5. 사용법

추후 pdf 파일 업로드 예정
