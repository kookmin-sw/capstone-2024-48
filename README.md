[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/omXkVCQu)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=14573272&assignment_repo_type=AssignmentRepo)
# 분산 신원(DID) 기반 학사증명 시스템

## 1. 프로젝트 소개

대학교에서 학생증, 성적증명서 등의 증명서를 종이 증명 대신에 분산 신원 기반 자격 증명 형태로 학생에게 발급해주고, 학생은 이러한 자격 증명을 모바일 지갑앱을 사용하여 외부인에게 제시한다. 자격 증명을 제시받은 외부인도 모바일 지갑앱을 통하여 자격 증명을 검증한다.
이때 자격 증명 보유자는 개인 정보 유출을 최소화하기 위해 발급된 자격 증명(학생증, 성적증명서 등)에서 개인정보 일부(주민번호 등)을 가리고 제시하거나 성인 여부만 제시할 수 있다.

## 2. Abstract (영문)
Universities issue certificates such as student IDs and transcripts to students in the form of distributed identity-based credentials instead of paper proofs, and students present these credentials to outsiders using a mobile wallet app. Outsiders who are presented with credentials also verify them through the mobile wallet app.
At this time, in order to minimize personal information leakage, the certificate holder can present some personal information (residential number, etc.) in the issued certificate (student ID, transcript, etc.) or present only the adult status.

## 3. 소개 영상 (Youtube , 스크린샷 모음 , 시연영상 등 , 추가링크 포함)
[![Video Label](http://img.youtube.com/vi/.jpg)](https://youtu.be/)

## 4. 팀 소개
|<img width="60" src="https://avatars.githubusercontent.com/u/55120700?s=400&u=6529f056a868415a5cfd27f1444be30876c2c8e3&v=4">|<img width="60" src="![Uploading KakaoTalk_20240405_092329329.jpg…]()>|
|---|---|
|[김수연(****1563)](https://github.com/suyeon1104)|이윤성(****1617)|

|기획/개발|디자인/테스트|
## 5. 사용법

소스코드 제출 시 설치법이나 사용법을 작성하세요.

공통
```bash
git clone https://github.com/kookmin-sw/capstone-2024-48.git
```

<details>
<summary>Client</summary>
<div markdown="1">
    cd src/client/
    go build
</div>
</details>

<details>
<summary>VDR Server</summary>
<div markdown="1">
    cd src/server/
    go build
</div>
</details>

<details>
<summary>Model</summary>
<div markdown="1">

    cd src/model
    pip install -r requirements.txt
    python fastapi/main.py

</div>
</details>
