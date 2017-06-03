name: inverse
layout: true
class: underscore, split-50

---
class: center, middle, hero

.title[
# 2017 IT21 Global Conference 발표자료

발표일: 2017.06.03
]

6월 1일, 2일  이틀간 삼성역 소재 섬유센터 17층에서 진행하는 2017 IT21 Global Conference 에 참가하였습니다.

---
# 발표 트랙

.c[
- 6월 1일
  - 기조연설
  - `빅데이터 딥러닝`
  - AR/VR과 4차 산업
  - 클라우드와 컨테이너
  - 주요 연구기관 세션
]
.c[
- 6월 2일
  - 기조연설
  - `언어지능과 머신러닝`
  - 차세대 보안
  - 지능형 임베디드 시스템
]

---
class: split-50

# 발표 내용

.c[
빅데이터 딥러닝
  - 머신러닝 기초 이론과 뉴럴 네트워크
  - Recurrent Neural Network과 Sequence to Sequence learning
  - 빅데이터를 위한 딥러닝 응용 사례
  - Visual Analytics via Real-Tiem Interactive 2D Embedding
  - 빅데이터분석플랫폼 Brightics
]

.c[
언어지능과 머시러닝
  - 엑소브레인 SW - 언어처리 및 질의응답 기술
  - 심층 신경망(Deep Neural Network)을 이용한 자연어처리 분석도구 개발
  - 인사이트 발굴을 위한 새로운 접근: Rebot Report Writing
  - 대화시스템 개발을 위한 자연어처리 기술
  - 딥러닝과 자연어생성
]

---

# 기조강연

## ICT 디바이스 현황 및 전망

- CES 2017
- MWC 2017

.footer[
- ICT란 정보 통신 기술(Information & Communication Technology)의 약자
]

---

# CES

- Consumer Electronic Show 줄여서 `CES` 입니다. 
- 전세계 적으로 메이져 전자회사와 업계 전문가들로 부터 명망이 있는 전자, 신기술 박람회 
- 매년 1월 미국 네바다 주 라스베가스의 라스베가스 컨벤션센터에서 열림

--

## 핵심키워드

- 인공지능
- 자율주행차
- VR/AR
- 사물인터넷

.footer[
- http://www.cesweb.org
- https://hongshinpark.me/2014/01/07/ces-란-무엇인가-ces-의-역사/
]

---

# MWC

- Mobile World Congress 줄여서 `MWC` 입니다.
- GSM 협회가 주관
- 매년 2월에 스페인 바르셀로나에서 열리는 모바일 산업 및 콘퍼런스를 위한 세계 최대의 박람회

--

## 핵심키워드

- 인공지능
- 5G
- IoT

.footer[
- https://ko.wikipedia.org/wiki/모바일_월드_콩그레스
]

---
# ICT 디바이스 국내외 현황

- 무인이동체
- 웨어러블
- 3D 프린팅
]


???
결론은 이런것들이 성장추세 이므로 이에 대한 준비를 잘하자 입니다.
CES, MWC를 지켜보며 트랜드 파악이 중요합니다.

---
class: split-60
# 머신러닝

.c[
![Right-aligned image](http://www.it-b.co.kr/news/photo/201608/12442_11749_543.jpg)
]
--
.c[
- 인공 지능: 인간의 지능을 기계로 구현하다
- 머신 러닝: 인공 지능을 구현하는 구체적 접근 방식
- 딥 러닝: 완전한 머신 러닝을 실현하는 기술
]


.footer[
    - http://www.it-b.co.kr/news/articleView.html?idxno=12442
]

???
위에서 여러 세션을 구분하였지만, 제가 이해할 수 있는 한계에서는 거의 동일하였기에 내용을 합칩니다.
큰 그림에서 보자면, 여러 강연자가 발표하였지만, 초보자에게는 발표자만 바뀌였을뿐, 내용이 같습니다.

---

# 머신 러닝 작동 방식에 의한 분류

## 지도 학습
- `분류` : 음성 인식, 신용 평가, 종양 악성, 양성 여부, 스팸 여부
- `회귀` : 온도 변화, 전력 부하 예측, 알고리즘 트레이딩

--

## 비지도 학습
- `클러스터링` : 유전자 서열 분석, 시장 조사, 객체 인식

.footer[
  - https://kr.mathworks.com/content/dam/mathworks/tag-team/Objects/k/93111v00_KR_machine_learning_section1_ebook.pdf
]

---
class: split-70

# 뇌 세포의 구성

.c[
![](http://cfile23.uf.tistory.com/image/17646D024B001F9E7B2184)
]

.c[
- 시냅스 : Synapse
- 세포체 : Soma
- 축삭돌기 : Axon
- 수상돌기 : Dendrite
]

---

# 결국 학습이란?

.c[
- 학습(Learning) 이란?
  - 시냅스 연결의 세기(strength)를 조정하는 것.
]

.c[
![](http://admin.brainworld.com/Library/FileDown.aspx?filename=edinkim_1411316210960.jpg&filepath=BrainScience)
]

---

# 머신 러닝 틀(Framework)

- 학습 데이터와 기대값(output label)을 이용해 예측 함수 $$f$$ 를 구하는 것

$$
y = f(x)
$$
- y = output
- f = prediction function
- x = training data

---
# 머신 러닝

.c[
- 씨앗 = Algorithms
- 비료 = Data
- 농부 = `You`
- 결실 = Programs
]

.c[
![](http://cfile23.uf.tistory.com/image/1637C9464DB3598E3B5179)
]

---

# 인공 신경망의 학습
- 인공 뉴런 네트워크가 단순 논리 회로와 다른 점.
  - 학습을 통해 `weight`와 `bias`를 조절이 가능

.c[
![](https://qph.ec.quoracdn.net/main-qimg-bf5a21006f36c6653a586b06da1a04f2)
]

.c[
![](http://jcsites.juniata.edu/faculty/rhodes/cs1/images/addercircuit.jpg)
]

---

# 인공 신경망의 구조

![](https://i.stack.imgur.com/OH3gI.png)

input layer, hidden layer, output layer

`Fully Connected Layer`

---

# Gradient Descent

.c[
![](https://sebastianraschka.com/images/faq/closed-form-vs-gd/ball.png)  
]

공을 어느 위치에서 떨어뜨리더라도 가장 낮은 곳에서 멈춤

![](https://sebastianraschka.com/images/faq/closed-form-vs-gd/dw.png)
![](https://sebastianraschka.com/images/faq/closed-form-vs-gd/w_upd.png)

---

# 학습방법

![](http://personal.ee.surrey.ac.uk/Personal/T.Windeatt/msc_projects/tambasis/WEB/Image5.jpg)

1. 학습 데이터 입력단에 인가. 이 때 각 net의 `가중치`나 `바이어스`는 적절한 초기값으로 설정.
2. 결과를 출력과 비교하여 error에 대한 `cost function`값을 구함
3. 가중치나 바이어스 조절을 위해, 편미분 값이 error에 어떤 영향을 끼치는지 확인
4. 편미분 값을 이용해서 가중치나 바이어스 값을 조절
5. (1~4) 과정을 반복적으로 수행  

---

# Machine Learning

- 선형회기

# Deep Learning


- CNN
- RNN

???
이런것이 있다라는 정도로만 설명하겠습니다.

---




