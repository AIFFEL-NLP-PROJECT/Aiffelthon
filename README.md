
# Project AIFFELTHON


<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white"> <a href="https://bejewled-roll-712.notion.site/3-1d0df2d63705479dabd40a4214d82417"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"></a>

## 💡프로젝트 소개
```
1️⃣ 주제 : 추상 요약을 사용한 대화문 요약 AI
2️⃣ 데이터셋 : AI Hub : 한국어 대화 데이터 (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=117)
3️⃣ 컬럼 : Id, Text(원문), Summary(대화 요약), Category(대화 유형)
4️⃣ 모델 : KoBART, KoGPT-2  
5️⃣ 간단 설명 : 채팅 속 일상 대화 및 기록된 구어체 문장을 아이템에 입력하면 생성 요약한 간결한 문장을 제공
```

---
## 팀 소개

### 세줄요약

|손기락|고도환|최지원|
|---|---|---|
||||
|- 팀장 </br>- Modeling(KoGPT-2) </br>- EDA 및 전처리|- PM </br>- Modeling(KoBART) </br>- 자료 조사|- 과업 정리 </br>- Modeling(KoGPT-2)|
|||||

---
## 🏅 프로젝트 목표
#### 1. 추상적 요약 결과 ROUGE-Score 0.3 이상 달성하기 🟩    

---
## 🗓️ 프로젝트 진행 일정

|내용|M1|M2|H1|H2|H3|H4|H5|
|---|---|---|---|---|---|---|---|
|데이터 EDA 및 전처리 방향 결정|🟡|🟡||||||
|Model 탐색|🟡|🟡|🟡|||||
|Basic 분석 시행|🟡|🟡||||||
|모델 선정|🟡|🟡||||||
|모델 구축 및 성능 개선|🟡|🟡|🟡|🟡|🟡|||
|결과 분석||||||🟡|🟡|

---
## 🦄 프로젝트를 위한 자료
#### [1. 데이터셋(AI Hub)](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=117)
#### [2. 논문 자료 바로가기](https://bejewled-roll-712.notion.site/5325673955d84493b83ccd31e044d6b3)
#### [3. 노션 페이지 바로가기](https://bejewled-roll-712.notion.site/3-1d0df2d63705479dabd40a4214d82417) 
#### [4. 학습 보충 자료](https://bejewled-roll-712.notion.site/StudyWithUs-97d1570c7863469eb37a9c405798376b)

---
## 📑 프로젝트 진행 과정
|No|내용|깃허브|관리대표|
|---|---|---|---|
|01|EDA 및 전처리|[📂](https://github.com/AIFFEL-NLP-PROJECT/Aiffelthon/tree/main/Data_EDA)|손기락|
|02|Modeling(1) - KoBART|[📂](https://github.com/AIFFEL-NLP-PROJECT/Aiffelthon/tree/main/Model/KoBART)|고도환|
|03|Modeling(2) - KoGPT-2|[📂](https://github.com/AIFFEL-NLP-PROJECT/Aiffelthon/tree/main/Model/KoGPT-2)|최지원, 손기락|
|04|논문 내용 정리|[📂](https://bejewled-roll-712.notion.site/5325673955d84493b83ccd31e044d6b3)|최지원|

---
## 🏆 프로젝트 결과(Rouge-Score)
|Model|KoGPT-2|KoBART|
|---|---|---|
|Recall|0.1873|0.2636|
|Precision|0.2543|0.2602|
|F1-Score|0.2078|0.2536|

---
## 🏆 프로젝트 결과(영상)    
[![Video Label](http://img.youtube.com/vi/NF_89j3lo1I/0.jpg)](https://youtu.be/NF_89j3lo1I)
