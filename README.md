oss_project
# 온라인 이러닝 플랫폼에 대한 (학습) 메타데이터

## EduCOR : An Educational and Career-Oriented Recommendation Ontology **[논문 링크](https://arxiv.org/abs/2107.05522)**

## - 개요
 **온라인 학습 플랫폼의 의존도가 증가**함에 따라,   
**디지털 학습 자원의 통합된 표현**은 동적 및 다중 소스 학습 경험을 지원하기 위해 **필수적**이다.   
 따라서 **개인화된 학습 시스템을 위한** 온라인 학습 자원을 표현하기 위해,   
 기초를 제공하는 교육적이고 경력 지향적인 온톨로지인 **"EduCOR ontology"** 를 소개한다.
   
 이러한 온톨로지는 **학습 자료 저장소**가 사용자의 학습에 해당하는 **학습경로 권장사항을 제공**할 수 있도록 **설계**된다.

## - [Resource](https://tibonto.github.io/educor/)
## - 키워드
: **온톨로지** / **교육 자원** / 교육 / **노동시장** / 스킬 / **학습 경로** / 사용자 프로필 / **개인화된 권장사항**

## 1. 소개
최근 디지털 교육은 ERs(교육 자원, Educational Resources)와 OER(개방형 교육 자원, Open Educational Resources)에 의존하고 있다.   
이때, ERs(교육 자원)은 비디오, 디지털 교과서, 강의의 오디오 녹음, 간단한 웹 페이지, 슬라이드 덱 등과 같이 다양한 형태로 이용 가능하다.   

ERs와 OER은 대게 저품질 메타데이터와 함께 제공되고, 다른 혹은 비슷한 내용상의 ER(교육 자원)들로부터 떨어져 있다.   

즉, 이는 OERS(개방형 교육 자원)에 기반한 고품질 서비스 (Ex. 추천 및 검색 서비스)가 부족한 이유 중 하나로 대두된다.   

공개적으로 사용 가능한 ER과 OER에 메타데이터를 향상시키는 것과 ERS를 분류하고 구성하는 것에 SW(the Semantic Web) 커뮤니티의 관심이 높아진 것은 놀랍지 않은 결과이다.   

많은 어휘들과 스키마가 제안되었지만, 그들 중 일부만 온라인에서 이용 가능함과 동시에 OERS의 특수성 및 개인화된 추천 시스템의 특징을 수용할 수 있다.   

교육 지식 그래프에 대한 관심이 증가했지만, 근본적인 온톨로지 or 스키마가 부족하다.   
또한, 상용 제품들은 그들의 기본 지식 스키마를 사용하지않거나 게시하지 않으므로 비슷한 방향을 따르는 것처럼 보인다. 

e-learning에 대한 설문조사에 따르면, 개인화된 추천 시스템을 달성하는 데 온톨로지가 도움이 되고
스마트 교육을 달성하기 위해 인공지능으로 현재의 도구를 풍부하게 하기 위한 교육 측면의 관심이 증가하고 있는 추세다.   
이러한 측면에서 온톨로지는 스마트 튜터링 시스템에 매우 다양한 이점을 제공한다.   

the SW(the Semantic Web)은 질문 답변 및 (학습) 추천 시스템에 상당한 초점을 맞추고 있다.  
(학습) 추천 시스템은 개인화된 학습 권장사항을 제공하면서, 상호운용성, 설명성 및 사용자 개인정보를 제공하도록 빠르게 발전하고 있다.   

사회는 교육의 디지털 전환에 엄청난 노력을 쏟고 있는데 (Ex. 유럽 연합의 디지털 교육 계획)   
일과 관련된 기술을 일치 시키고, 온라인 학습 플랫폼에서 기술을 개발하고 있다.   

COVID-19 범유행 기간 동안 온라인 학습 플랫폼은 수백만명의 학습자에 의해 매일 사용되고 있다.   
결과적으로 직업변화, (재)기술 또는 실업기간 후 노동시장에 (재)진출하는 사람들을 도울 수 있는 평생학습 도구의 필요성이 대두되고 있다.   

복잡한 학습 환경에서 학습 프로세스를 모델링하는 새로운 방법이 필요하므로 교육의 개인화 어젠다가 필요하다.  
하지만, 이는 특히 학습 과정의 구성요소(Ex. 교육(학습 콘텐츠 및 교육), 노동시장(학습 컨텍스트), 학습자의 개별 요구(학습 목표))가 유래되었을 때 어렵다.   
e-learning 및 직업 온톨로지로서 사용할 수 있는 직업은 많으나, 현재 이 두 도메인을 연결할 수 있는 모델은 없다.   
따라서 SW와 더 광범위한 지역사회의 관심에 따라 교육 및 경력 지향 추천 온톨로지인 "EduCOR ontology"를 개발하게 되었다.   
이는 풍부한 메타데이터를 ER, 기술 및 사용자의 프로필을 설명한다.   

**[EduCOR의 역할]**
1) 개인화된 OER 추천 시스템을 위한 잠재적 프레임 워크
2) 교육 지식 그래프의 기초를 모두 제공
- 학습자의 학습 경로와 사용자의 프로필을 기반으로, 개인화된 추천 시스템을 위한 ER 모델링에서 새로운 장을 열고 있다.
- 개인화된 학습 추천 시스템과 교육 데이터 및 기술을 노동시장과 연결하는데 있어 필수적인 격차를 메우고 있으므로 향후 응용에 필수적인 스키마가 되고 있다.   

## 2. EduCOR Ontology
**[EduCOR ontology 제안 목적]**
1) 공통 온톨로지 하에 서로 다른 ER 및 OER를 구성
2) 노동시장에 연결
3) e-learning 도메인에서 개인화된 추천 시스템을 제공

결론적으로, 온톨로지를 구성하는 주요 구성 요소를 식별한다.

**2-1. 온톨로지 구성**   
 이 온톨로지는 개인화된 권장 사항을 지원하는 e-learning 환경을 구성하는데 필요한 클래스 및 속성을 소개한다.
 한편, IEEE LOM Standard7과 LRMI Standard8를 채택 & CSSO 및 Schema.org의 부품을 재사용 한다.
 온톨로지 표현을 위해 OWL을 사용하고, FARE 원칙을 따라 이에 대한 참조를 포함하는 어휘를 재사용 한다.
 다른 온톨로지를 매핑하여 보다 구체적인 활용도를 얻을 수 있는 플러크인 포인트로 클래스를 제공한다.
   
**2-2. 패턴**   
 EduCOR은 온톨로지의 완전한 스키마를 만들기 위해 결합될 수 있는 독립적인 모듈로 구성된다.
 이때, 모듈을 패턴이라고도 한다.
 요구사항 분석을 기반으로 개인화된 학습 추천 시스템의 주요 구성 요소를 식별했다.

**EduCOR가 식별하는 패턴**
- 교육 자원
- 지식 주제
- 기술
- 학습 경로
- 테스트
- 권장사항
- 사용자 프로필

**패턴 특성**
- 각 패턴은 단독으로 존재한다.   
- 응용 프로그램이 해당 패턴을 필요로 하거나 필요로 하지 않을 경우 EduCOR 온톨로지로부터 분리된 단일 패턴으로 사용되는 다른 온톨로지에 추가할 수 있다.   

---

![그림 1.](https://tibonto.github.io/educor/EduCOR.png)

### [그림 1.] 분석
- 각 패턴의 클래스는 서로 다른 색상으로 표시   

---

**1) 패턴 A**   
- Educational Resource(교육 자원) 패턴에서 'Educational Resource(교육 자원)' 클래스는 학습 자료 or 학습 대상을 나타냄.
- 'Multimedia Data(멀티미디어 데이터)' 클래스에서 다루는 여러가지 유형을 가질 수 있음.

- 'Educational Resource'에는 호스팅 콘텐츠 저장소에서 요구하는 모든 품질 측정값을 반영하는 'Quality Indicator(품질 지표)'이 있음.   
- 'Accessibility(접근성)' 클래스를 통해 학습자의 다양한 접근 요구사항을 학습자료의 접근권한과 방법을 다룸.   
- 또한 'Educational Resource(교육 자원)'은 Knowledge Topic(지식 주제) 패턴 D의 특정 'Knowledge Topic'을 나타냄.   

**2) 패턴 D**
- Knowledge Topic(지식 주제)은 특정 지식영역의 특정 주제를 나타냄.   
(Ex. 'Mathmatics(수학)' 영역의 'Quadratic Equations(이차방정식)') 

- 'Knoledge Topic(지식 주제)'은 학습자가 특정 'Methodology(방법론)'을 통해 경험하는 'Theory(이론)'과 'Exercise(연습)' 내용이 있다.
- 이때, 'Exercise(연습)' 클래스는 'Knowledge Topic(지식 주제)'과 'Test(연습)' 패턴에 모두 연결됨.   

## 3. 사용 사례 시나리오   
## 4. 평가   
**4-1. Gold standard-based 평가**   
**4-2. Task-based 평가**
## 5. 관련 작업      
## 6. 토론 및 향후 단계      
## 7. 결론
=======
## Introduction

 온라인 학습 플랫폼은 특정 COVID-19 펜데믹 기간 동안 매일 백만명의 학습자들에 의해 사용되어지고 있으며, 교육 체제는 전세계적으로 온라인 환경으로 향하고 있다. 그러므로 장기적인 학습 툴은 직업 변화, (재)숙련 혹은 실업 후 노동 시장으로의 (재)입장에서 사람들을 보조할 수 있도록 부상되어진다. 이러닝과 직업 온톨로지들로 이용 가능한 수많은 작업들이 있는 반면에 두 개의 도메인들 (Educational Resources(ERs) & Open Educational Resources(OER))을 연결하기 위해 이용가능한 모델은 현재 존재하지 않는다. 그리하여 EduCOR 온톨로지가 공통 온톨로지 하에 다른 도메인인 ERs와 OERs를 정리하고, 노동 시장을 연결하고, 이러닝 플랫폼 내 개인화된 추천 시스템을 제공하도록 제안되었다.

## Method & authutorial

 온톨로지는 개인화된 추천을 지원하는 이러닝 환경을 구성하는 classes와 properties를 필수적으로 가지고 있다.

### 1. 온톨로지 구성

 온톨로지를 개발하기 전 관련 최신 작품, 개방형 standard 그리고 모범 사례를 조사한다. 이 과정에서 교육적인 내용과 관련된 개방형 표준의 묶음들을 조사하고, 좁은 범위보다는 넓은 적용 범위를 제공하는 것으로 비판적인 선택을 한다. 따라서, 널리 사용되는 IEEE LOM standard와 LRMI standard를 선택하였고, Curriculum Course Syllabus Ontology (CCSO)과 schema.org 의 일부분을 재사용하였다. 이후 온톨로지를 FAIR principles로 정렬한다. 온톨로지 표현을 위해 OWL을 사용, FAIR principles를 따르는 용어들을 재사용하고 그들에 대한 reference들을 기입한다. 이후 데이터의 범위를 묘사하고, licence CC0 1.0 Universell (CC0 1.0) Public Domain Dedication 하에 출판한다. 디자인을 끝내기 전, 전문가의 평가 단계를 거치면서 도메인 전문가와 온톨로지 전문가에게서 피드백을 받았다.

### 1-1. EduCOR 온톨로지를 구성하는 다중 패턴들 (도메인간 적용 가능성과 다른 온톨로지간의 상호 운용성을 강조)

 EduCOR는 온톨로지의 완전한 스키마를 생성하기 위해 결합될 수 있는 독립적인 모듈로 구성되어 있다. 이러한 모듈을 패턴이라고 칭할 수 있다. EduCOR를 식별하는 다중 패턴에는 `Educational Resource, Knowledge Topic, Skill, Learning Path, Test, Recommendation, User Profile`의 총 6가지 패턴이 존재한다. 각 패턴은 홀로 쓰일 수 있고, 다른 온톨로지에 더해질 수 있으며 EduCOR 온톨로지로부터 분리되어 단일의 패턴으로써 사용될 수 있다.

![EduCOR](https://user-images.githubusercontent.com/101023626/166270342-cc0d7641-b49c-4d70-bb40-105ca7aaf49b.png)

### 2. 사용 경우의 시나리오

### 2-1. 보편적인 시나리오

 OER 레퍼지토리 소유자는 그들의 레퍼지토리에 학습 자료들을 모델링 하기 위해 EduCOR 온톨로지를 활용할 수 있다. 따라서 레퍼지토리는 standard 검색 및 정보 검색 기능을 통해 학습자에게 서비스를 제공할 수 있다. 향후 미래에는 레퍼지토리 구조를 최소 0으로 조정하여 자동 의사 결정 지원 시스템을 통합하는 것이 가능할 수 있다.

### 2-2. 특정한 경우의 시나리오

 데이터 과학 관련 작업에 중점을 둔 개방형 학습 추천 시스템 프로토타입인 eDoer12 플랫폼의 개발에서 온톨로지를 사용하는 경우다. 개방을 통해 학습자에게 노동 시장 정보와 OERs에 근거한 개인화된 학습과 커리큘럼 추천하는 권한을 부여하는 것을 목표로하는 eDoer은 EduCOR 온톨로지를 사용하여 다음과 같은 구성 요소로 전개되어질 수 있다.
 
먼저, 직업과 해당 직업이 필요로하는 품질 사이를 잇는 `Skill` 패턴을 사용한다. 그리고 관련 있는 학습 구성요소들 내에 각 기술을 분해하는 `Knowledge Topic` 패턴을 추가한다. `Learning Path` 패턴은 목표 직업 또는 기술과 같은 학습 목표를 향한 일련의 지식 주제를 포함하는 학습자를 위한 경로를 만드는 데 사용된다. 이후 시스템 내에 필요한 학습 자원들을 저장하기 위해 `Educational Resource` 패턴을 추가하였다. 개인화된 학습 콘텐츠 추천 엔진을 구축하는 과정에서, 학습자의 학습 목표, 학습 선호도, 그리고 현재 지식 수준에 근거하여 학습자에게 가장 관련있는 학습 아이템들을 제공하여 `Recommendation` 및 `User Profile` 패턴으로부터 이익을 받는다. `Test` 패턴은 학습자가 학습 목표를 향한 진행 상황을 모니터링할 수 있도록 평가 서비스를 제공하는 데 사용되었다.

### 3. 평가

 객관성을 보장하기 위해 귀납법을 사용할 것이다. 따라서, EduCOR 온톨로지의 핵심 성과 지표(KPI)로서 수업별로 학습 자료를 설명하는 능력을 의미하는 `적용 범위`와 여러 저장소를 균일하게 나타낼 수 있는 가능성을 의미하는 `적응성`에 집중할 것이다.

### 3-1. 골드 standard 기반 평가

 EduCOR를 다른 저장소 스키마와 직접 비교하기 위한 것이다.

### 3-2. 업무 기반 평가

 실제 사용 사례에서 성능을 검증하기 위한 것이다.

## Results

 교육적인 도메인, 개인화된 학습 추천 시스템들, 사용자 프로필 그리고 노동 시장 데이터를 모델링하는 것을 목표로 무료 접근 온톨로지인 오픈 소스를 만들었다. 시멘틱 웹을 위해, 교육자들과 더 넓은 커뮤니티는 모두 중요하다. 주의깊게 만들어진 역량 질문들을 통해, 디자이너의 시스템을 위해 필요한 요소들을 측정할 수 있는 추천 시스템에 근거한 이러닝 내 시스템 디자이너들을 보조하는 EduCOR 능력을 평가하였다. 개발된 온톨로지는 디자이너들의 추천 시스템 내 디자이너들이 구현하는 개인화된 기능들로써 시스템 디자이너들에게 유익한 툴이 되리라 생각한다. 이후에도 온톨로지를 확장할 미래 요구 사항들을 지원하는 방향으로 해당 작업 라인에 계속하여 전념할 것이다.

## Discussion

 EduCOR는 Computer Science 혹은 온라인 학습 플랫폼과 개인화된 교육 시스템들을 지지하는 것과 같은 다른 교육적인 도메인들에서 사용되어질 수 있다. EduCOR는 필수적인 용어와 다른 환경에서 충분히 일반적으로 사용되어질 수 있는 충분한 메타데이터가 풍부하다. 섹션으로써 보여지는 Massive Open Online Courses (MOCC) 그리고 OERs와 관련된 기존의 교육적인 저장소들과 함께 호환성을 활용하고 유지할 수 있다. 추천 시스템의 구성요소 모델링에 필요한 개인화 표현 요소를 포함하기 위해 MOCC와 OERs를 확장하였다.

 EduCOR는 응용 프로그램 도메인에 특정 데이터를 공급하지 않고, 도메인 특정 온톨로지를 EduCOR 온톨로지에 매끄럽게 정렬하기 위해 전문가의 개입이 필요할 수 있다. 또한, 온톨로지에 코스들을 자동 mapping 할 수 없고, 커리큘럼을 제공하지 않는다.

## Future Steps

 OERs 및 추천 시스템의 몇 가지 측면에서 보다 철저한 분석이 필요할 수 있다. 또한, 접근성 분석은 시스템의 추가적인 표현 제공으로 확장될 수 있다. 미래 작업의 토대로 EduCOR 온톨로지를 사용하는 방향으로써 다음해에 지속 가능한 계획을 예측해야 한다.
 main
