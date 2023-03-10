# 소프트웨어 설계_요구사항 확인

## 요구사항 확인

### 현행 시스템 분석

******************************************플랫폼 기능 분석******************************************

플랫폼

- 어플리케이션을 구동시키는 데에 필요한 소프트웨어의 환경
- 동일 플랫폼 내에서는 상호호환이 가능하도록 만들어진 결합체
- 공급자와 수요자 등 복수 그룹이 참여하여 각 그룹이 얻고자 하는 가치를 공정한 거래를 통해 교환할 수 있도록 구축된 환경

플랫폼 유형

- 싱글 사이드 플랫폼: 제휴 관계를 통해 `소비자와 공급자`를 연결하는 형태 (아이튠즈, 안드로이드 마켓)
- 투 사이드 플랫폼: `두 그룹을 중개`하고 모두에게 개방하는 형태 (소개팅 앱)
- 멀티 사이드 플랫폼: `다양한 이해관계 그룹`을 연결하여 중개하는 형태 (페이스북, 인스타그램)

플랫폼 기능

- 소프트웨어 개발과 운영비용 감소, 생산성 향상
- 동일 그룹 플랫폼의 커뮤니티 형성, 네트워크 효과 유발

플랫폼 기능 분석 절차

1. 현행 플랫폼 자료 수집
2. 수집 자료 분석
3. 결과 산출물 작성

**********************************************************플랫폼 성능 특성 분석**********************************************************

분석의 이유

- 사용자의 서비스 이용 시 속도의 적정성을 알 수 있음
- 사용자 요구사항 중 성능에 대한 개선요청 항목은 현재 시스템 플랫폼 성능이 느린 것으로 제기될 가능성이 있음

분석 기법

- 사용자 인터뷰: 현행 플랫폼 사용자 인터뷰를 통해 속도의 적정성 확인
- 성능 테스트: 현행 플랫폼을 대상으로 성능, 부하 테스트 수행
- 산출물 점검: 현행 플랫폼과 유사한 타사 제품의 성능 자료 등 분석

플랫폼 성능 특성 측정 항목

- 경과 시간
- 사용률
- 응답시간
- 가용성

**운영체제 분석**

운영체제

- 하드웨어 및 소프트웨어 자원을 효율적으로 관리하며 공통된 기능을 제공하는 소프트웨어
- 사용자가 컴푸터를 더 쉽게 사용할 수 있게 지원하는 소프트웨어

운영체제 현행 시스템 분석

- 품질 측면; 신뢰도, 성능
- 지원 측면; 기술 지원, 주변 기기, 구축 비용

종류

- 컴퓨터: Windows, UNIX, Linux, etc.
- 모바일: 안드로이드, iOS, etc.

**네트워크 분석**

네트워크

- 컴퓨터 장치들이 노드 간 연결(데이터 링크)을 사용하여 서로에게 데이터를 교환하는 기술
- 데이터 링크는 유선 매체(광케이블) 혹은 무선 매체(와이파이)를 통해 성립

네트워크 현행 시스템 분석

- 현행 시스템이 구성된 네트워크 구조를 네트워크 구성도를 통해 분석
- 네트워크 구성도의 작성을 통해 서버 위치, 서버 간 연결 방식 파악 가능
- 백본망, 라우터, 스위치, 게이트웨이, 방화벽 등을 대상으로 분석
- 물리적 위치 관계 파악, 조직 내 보안 취약성 분석 및 대응이 쉬움
- 네트워크 장애 발생 추적 및 대응 등의 다양한 용도로 활용 가능

**********************DBMS 분석**********************

DBMS: 데이터베이스라는 데이터의 집합을 만들고 저장 및 관리할 수 있는 기능들을 제공하는 응용 프로그램

DBMS의 기능

- 중복 제어
- 접근 통제
- 인터페이스 제공
- 관계 표현
- 샤딩/파티셔닝
- 무결성 제약조건
- 백업 및 회복

DBMS 현행 시스템 분석 (고려사항)

- 성능 측면: 가용성, 성능, 상호 호환성
- 지원 측면: 기술 지원, 구축 비용

**********비즈니스 융합 분석**********

비즈니스 융합

- 융합 기술이 제공하는 기회나 융합의 원리를 적용해 새로운 제품, 서비스, 산업을 창출하거나 기존 제품을 혁신하기 위한 기업 활동
- 산업 또는 시장 간 경계를 허물어 정보통신 기술을 적용해 새로운 비즈니스 모델로의 범위 확대

비즈니스 융합 유형

- 고객 가치(why): 개인, 사회, 인류의 행복과 번영을 위한 가치 창출
- 시장 유통(whom): 신시장 개척 또는 미래시장 선점
- 가치 제안(what): 시장 혹은 고객의 미충족 욕구 대응을 위한 신상품 개발
- 공급 역량(who): 신기술, 신규 역량을 활용한 상품생산 및 판매
- 생산 방식(how): 제품 및 서비스의 생산, 판매 프로세스 혁신

비즈니스 융합 분석 절차

1. 기업전략 분석
2. 영역 및 방향 설정
3. 포트폴리오 선정
4. 융합모델 설계 및 평가
5. 비즈니스 융합 실행 및 개선

### 요구사항 확인

********************************요구분석 기법********************************

요구분석

- 사용자의 요구를 추출하여 목표를 정하고 어떤 방식으로 해결할 것인지 결정하는 단계
- 개발 대상에 대한 사용자의 요구사항 중 명확하지 않거나 모호하여 이해되지 않는 부분을 발견하고 이를 걸러내기 위한 과정

요구분석 특징

- 소프트웨어 개발의 실제적인 첫 단계로, 사용자의 요구에 대해 이해하는 단계
- 분석 결과의 문서화를 통해 향후 유지보수에 유용하게 활용 가능
- 보다 구체적인 명세를 위해 소단위 명세서가 활용될 수 있음
- 개발 비용이 가장 많이 소요되는 단계는 아님 (그건 유지보수 단계)
- 도메인 분석은 요구에 대한 정보를 수집하고 배경을 분석하여 이를 토대로 모델링함

요구사항 분석 단계 절차

1. 요구사항 분류
    1. 요구사항 유형[기능 요구사항, 비기능 요구사항]을 확인하는 단계
    2. 요구사항이 소프트웨어에 미치는 영향의 범위 파악
    3. 요구사항이 소프트웨어 생명주기 동안 변경이 발생하는지를 확인
2. 개념 모델링 생성 및 분석
    1. 요구사항을 더 쉽게 이해할 수 있도록 현실 세계의 상황 단순화, 개념적으로 표현한 것을 모델이라 하고, 모델링은 이러한 모델을 만드는 단계
    2. 객체 모델, 데이터 모델, 상태 모델 등 다양한 모델 작성 가능
    3. 모델링 표기를 위해 DFD, UML 다이어그램, ERD 사용
3. 요구사항 할당
4. 요구사항 협상
5. 정형 분석

요구사항 분석 기술

- 청취 기술
- 인터뷰와 질문 기술
- 분석 기술
- 중재 기술
- 관찰 기술
- 작성 기술
- 조직 기술
- 모델 작성 기술

요구사항 분석에 사용하는 기능 모델링 기법

- 데이터 흐름도
    - 개념
        - 데이터가 각 프로세스를 따라 흐르면서 변환되는 모습을 나타낸 그림
        - 시스템 분석과 설계에서 사용됨
        - 시스템의 모델링 도구로, 가장 보편적으로 사용되는 것 중 하나
        - 자료 흐름 그래프 또는 버블 차트라고 함
    - 특징
        - 구조적 분석 기법에 사용
        - 데이터의 흐름에 중심을 둠
        - 제어의 흐름은 중요하지 않음
        - 시간 흐름을 명확히 표현 불가능
    - 구성요소
        - 처리기(process) - 원
        - 데이터 흐름(data flow) - 화살표
        - 데이터 저장소(data store) - 평행선
        - 단말(terminator) - 사각형
- 자료사전
    - 개념
        - 자료 요소, 자료 요소들의 집합, 자료의 흐름, 자료 저장소의 의미와 그들 간의 관계, 관계 값, 범위, 단위들을 구체적으로 명시하는 사전
        - 파일 혹은 데이터베이스에 있는 자료에 대한 자료 또는 각 자료 항목에 주어진 이름과 길이 그리고 서술과 같은 데이터를 포함하는 참조를 위한 작업
    - 작성 목적
        - 조직에 속해 있는 다른 사람들에게 특정한 자료 용어가 무엇을 의미하는지를 알려주기 위해, 용어의 정의를 조정하고 취합하고 문서로 명확히 하는 목적이 있음
        - 자료 흐름도에 나타나는 어떤 자료의 흐름도 자료 사전에 정의되어 있어야 함
    - 기호
        - `=`: 자료의 정의. ~으로 구성되어 있다는 것을 나타내는 기호. 주석을 사용하여 의미를 기술하며, 자료 흐름과 자료저장소에 대한 구성 내역을 설명하고 자료 원소에 대하여 값이나 단위를 나타내는 기호
        - `+`: 자료의 연결(and, along with)을 나타내는 기호
        - `()`: 자료 생략 가능함을 나타내는 기호
        - `{}`: 자료의 반복을 나타내는 기호. 반복 횟수를 기록하는 데 {}에서 좌측에는 최소 반복 횟수를 기록하고 우측에는 최대 반복 횟수 기록
        - `[]`: 자료의 선택을 나타내는 기호. 택일 기호 `[ | ]`는 `|`로 분리된 항목 중 하나가 선택된다는 것을 표시
        - `**`: 자료의 설명을 나타내는 기호. 주석
    - 원칙
        - 자료의 의미 기술 → 주석을 통해 기술. 중복 기술 회피
        - 자료 구성항목의 기술 → 구성항목들을 그룹으로 묶음. 각 그룹에 대하여 의미 있는 이름 부여. 이름이 붙여진 각 그룹을 다시 정의
        - 동의어 규정 준수 → 사용자마다 동일한 문서나 자료에 대해 서로 다른 이름들을 갖고 있을 수 있으며, 사용자들의 용어를 통일시키는 것보다는 사용하는 용어를 이용하여 자료를 정의하는 것이 간단함
        - 자료 정의의 중복 제거 → 동일한 자료에 대해 여러 명의 분석가가 독립적으로 분석을 시행한다면, 서로 다른 이름을 사용할 수 있기 때문에 자료 정의의 중복 제거 필요

요구사항 분석이 어려운 이유

- 개발자와 사용자 간의 지식이나 표현의 차이가 커서 상호 이해가 쉽지 않음
- 사용자의 요구사항이 모호하고 불명확
- 소프트웨어 개발 과정 중 요구사항이 계속 변할 수 있음
- 사용자의 요구는 예외가 많아 열거와 구조화가 여러움

******UML******

UML: 객체 지향 소프트웨어 개발 과정에서 산출물을 명세화, 시각화, 문서화할 때 사용되는 모델링 기술과 방법론을 통합해서 만든 표준화된 범용 모델링 언어

특징

- 가시화 언어: 개념 모델 작성 시 오류가 적고 의사소통이 용이
- 구축 언어: 다양한 프로그래밍 언어로 실행 시스템의 예측 가능. UML을 소스코드로 변환하여 구축 가능. 역변환하여 역공학 가능
- 명세화 언어: 정확한 모델 제시, 완전한 모델 작성 가능
- 문서화 언어: 시스템에 대한 평가 및 의사소통의 문서

구분

- 구조적 다이어그램(Structural Diagram) / 정적 다이어그램(Static Diagram)
    - 클래스(Class)
        - 시스템 내 클래스의 정적 구조를 표현
        - 속성(Attribute)와 동작(Behavior)으로 구성
        - 시스템의 구조를 파악하고 구조상의 문제점 도출 가능
        - 클래스와 클래스, 클래스의 속성 사이의 관계 표현
    - 객체(Object)
        - 클래스에 속한 사물(객체)들, 즉 인스턴스를 특정 시점의 객체와 객체 사이의 관계로 표현
        - 객체 인스턴스를 나타내는 대신 실제 클래스 사용
        - 연관된 모든 인스턴스 표현
    - 컴포넌트(Component)
        - 코드 컴포넌트 기반의 물리적 구조 표현
        - 실질적 프로그래밍 작업에 사용
    - 배치(Deployment)
        - 컴포넌트 사이의 종속성을 표현
        - 결과물, 프로세스, 컴포넌트 등 물리적 요소들의 위치 표현
    - 복합체 구조(Composite Structure)
        - 클래스나 컴포넌트가 복합 구조를 갖는 경우 그 내부 구조를 표현
    - 패키지(Package)
        - 유스케이스나 클래스 등의 모델 요소들을 그룹화한 패키지들의 관계를 표현
- 행위적 다이어그램(Behavioral Diagram) / 동적 다이어그램(Dynamic Diagram)
    - 유스케이스(Usecase)
        - 사용자 관점에서 시스템의 활동 표현
        - 시스템의 기능적 요구 정의에 활용
    - 시퀀스(Sequence)
        - 객체 간 상호 작용을 메시지 흐름으로 표현
        - 객체 사이 메시지를 보내는 시간을 표현
        - 교류 다이어그램(Interaction Diagram)의 한 종류로 볼 수 있음
    - 커뮤니케이션(Communication)
        - 시퀀스 다이어그램과 같이 동작에 참여하는 객체들이 주고받는 메시지를 표현하는데, 메시지뿐만 아니라 객체 간의 연관까지 표현
    - 상태(State)
        - 하나의 객체가 자신이 속한 클래스의 상태 변화 혹은 다른 객체와의 상호 작용에 따라 상태가 어떻게 변화하는지 표현
        - 모든 가능한 상태와 전이를 표현
        - 진입 조건, 탈출 조건, 상태 전이 등 기술
    - 활동(Activity)
        - 시스템이 어떤 기능을 수행하는지를 객체의 처리 로직이나 조건에 따른 처리의 흐름으로 순서대로 표현
        - 활동의 순서대로 흐름을 표현
    - 타이밍(Timing)
        - 객체 상태 변화와 시간 제약을 명시적으로 표현

UML 상세

- 클래스 다이어그램
    - 개념
        - 객체 지향 모델링 시 클래스의 속성 및 연산과 클래스 간 정적인 관계를 표현한 다이어그램
        - 클래스와 클래스, 즉 클래스 속성 사이의 관계를 표현
    - 구성요소
        - 클래스 이름
        - 속성: 클래스의 특징에 이름을 부여
        - 연산: 클래스에 속하는 객체에 적용될 메서드 정의. 클래스의 동작을 의미하며, UML에서는 동작에 대한 인터페이스를 지칭함
        - 접근제어자(접근제한자): 클래스에 접근할 수 있는 정도를 표현
            - `-`: 클래스 내부접근만 허용(private)
            - `+`: 클래스 외부접근을 허용(public)
            - `#`: 동일 패키지 혹은 파생 클래스에서 접근 가능(protected)
            - `~`: 동일 패키지 클래스에서 접근 가능(default)
- 유스케이스 다이어그램
    - 개념
        - 시스템이 제공하고 있는 기능 및 그와 관련된 외부 요소를 사용자의 관점에서 표현하는 다이어그램
    - 구성요소
        - 유스케이스(Usecase)
            - 시스템이 제공해야 하는 서비스
            - 액터가 시스템을 통해 수행하는 일련의 행위
        - 액터(Actor)
            - 사용자가 시스템에 대해 수행하는 역할
            - 시스템과 상호 작용하는 사람 또는 사물
            - 액터명은 물리적인 사람이나 조직명보다는 역할 중심으로 추상화하여 정의해야 함
            - 필수 항목 중심으로 최소화하여 만들어야 함
            - 하나의 액터는 여러개의 유스케이스와 상호작용(Interact) 가능
        - 시스템(System)
            - 전체 시스템의 영역 표현
    - 구성요소 간의 관계
        - 연관관계(Association)
            - 유스케이스와 액터 간의 상호작용이 있음을 표현
            - 유스케이스와 액터를 실선으로 연결
        - 포함관계(Include)
            - 하나의 유스케이스가 다른 유스케이스의 실행을 전체로 할 때 형성되는 관계
            - 화살표를 점선으로 연결하고 `<<include>>`라고 표기. (기능을 포함하는 유스케이스)→(기능에 포함되는 유스케이스)
        - 확장관계(Extend)
            - 특정 조건에 따라 확장 기능 유스케이스를 수행하는 관계
            - 화살표를 점선으로 연결하고 `<<extend>>`라고 표기. (확장 대상 유스케이스)←(확장 기능 유스케이스)
        - 일반화 관계(Generalization)
            - 유사한 유스케이스 또는 액터를 모아 추상화한 유스케이스 또는 액터와 연결시켜 그룹을 만들어 이해도를 높이기 위한 관계
            - 실선 빈 삼각형 화살표로 (추상적인 유스케이스)←(구체적인 유스케이스) 연결
- 시퀀스 다이어그램
    - 개념
        - 객체 간 상호 작용을 메시지 흐름으로 표현한 다이어그램
    - 구성요소
        - 객체(Object)
            - 위쪽에 표시되며 아래로 생명선을 가짐
            - 사각형 안에 밑줄 친 이름으로 명시
        - 생명선(Lifeline)
            - 객체로부터 뻗어 나가는 점선
            - 실제 시간이 흐름에 따라 객체의 생명주기 동안 발생하는 이벤트 명시
        - 실행(Activation)
            - 직사각형은 오퍼레이션(함수)이 실행되는 시간을 의미
            - 직사각형이 위아래로 길어질수록 오퍼레이션 수행시간이 긺
        - 메시지(Message)
            - 객체 간의 상호작용은 메시지 교환으로 이루어짐
            - 한 객체에서 다른 객체로의 메시지를 전달하여 전달받은 객체의 오퍼레이션을 수행
            - 꽉찬 삼각형 실선 화살표로 표기하고 그 위에 메시지 명시
        - 회귀 메시지(Self-Message)
            - 같은 객체에 대한 함수(메서드)를 호출
            - 본인의 Lifeline으로 회귀하는 화살표로 표현

UML의 관계

- 연관(Association) 관계
    - 2개 이상의 사물이 서로 관련된 상태를 표현하는 관계
    - 사물 사이를 실선으로 연결하여 표현하며, 방향성은 실선 화살표로 표현
    - 서로에게 영향을 주는 양방향 관계의 경우 화살표를 생략하고 실선으로만 연결
- 의존(Dependency) 관계
    - 사물 사이에 서로 연관은 있으나 필요에 따라 서로에게 영향을 주는 짧은 시간 동안만 연관을 유지하는 관계를 표현하는 관계
    - 사물의 변화가 다른 사물에도 영향을 미치는 관계
    - 일반적으로 한 클래스가 다른 클래스를 오퍼레이션의 매개변수로 사용하는 경우에 나타나는 관계
    - 영향을 주는 사물이 영향을 받는 사물 쪽으로 점선 화살표를 연결하여 표현
- 일반화(Generalization) 관계
    - 하나의 사물이 다른 사물에 비해 더 일반적이닞 구체적인지를 표현하는 관계
    - 일반적인 개념을 부모(상위)라고 하고, 구체적인 개념을 자식(하위)이라 함
    - 구체적(하위)인 사물에서 일반적(상위)인 사물 쪽으로 속이 빈 화살표를 연결하여 표현
- 실체화(Realization) 관계
    - 한 객체가 다른 객체에 오퍼레이션을 수행하도록 지정하는 관계를 표현하는 관계
    - 사물에서 기능 쪽으로 속이 빈 점선 화살표를 연결하여 표현
- 포함(Composition) 관계
    - 집합 관계의 특수한 형태로, 포함하는 사물의 변화가 포함된느 사물에 영향을 미치는 관계를 표현하는 관계
    - 포함되는 쪽(부분)에서 포함하는 쪽(전체)으로 속이 채워진 마름모를 연결하여 표현
    - 부분←<>전체
- 집합(Aggregation) 관계
    - 하나의 사물이 다른 사물에 포함된 관계를 표현하는 관계
    - 포함된느 쪽(부분)에서 포함하는 쪽(Whole)으로 속이 빈 마름모를 연결하여 표현

UML 확장 모델의 스테레오 타입

- UML의 기본적 요소 이외의 새로운 요소를 만들어 내기 위한 확장 메커니즘
- 형태는 기존의 UML의 요소를 그대로 사용하지만 내부 의미는 다른 목적으로 사용하도록 확장
- UML의 스테레오 타입은 `<<>>`(길러멧; Guillemet) 기호를 사용하여 표현
- 유형
    - <<include>>
        - 하나의 유스케이스가 어떤 시점에 반드시 다른 유스케이스를 실행하는 포함 관계
    - <<extend>>
        - 하나의 유스케이스가 어떤 시점에 다른 유스케이스를 실행할 수도 있고, 그렇지 않을 수도 있는 확장 관계
        - 기본 유스케이스 수행 시 특별한 조건을 만족할 때 수행
    - <<interface>>
        - 모든 메서드가 추상 메서드이며, 바로 인스턴스를 만들 수 없는 클래스로 추상 메서드와 상수만으로 구성된 클래스
    - <<entity>>
        - 일반적으로 정보 또는 오래 지속되는 연관된 행위를 형상화하는 클래스로 유스케이스 처리 흐름이 수행되는 과정에서 기억장치에 저장되어야 할 정보를 표현하는 클래스
    - <<boundary>>
        - 시스템과 외부 액터와의 상호 작용을 담당하는 클래스
    - <<control>>
        - 시스템이 제공하는 기능의 로직 및 제어를 담당하는 클래스

**애자일(Agile)**

애자일 방법론: 소프트웨어 개발방법론의 하나로, 개발과 함께 즉시 피드백을 받아서 유동적으로 개발하는 방법

등장 배경; 기존 개발방법론의 한계를 극복하기 위해 등장

- 소프트웨어 개발 환경의 변화
    - 소프트웨어 개발 트렌드가 모바일 환경으로 변화
    - 시장 적시성과 잦은 배포의 중요성 부각
- 기존 개발방법론의 한계
    - 전통적 방법론은 문서 및 절차 위주로 변화에 신속한 대응이 어려움
    - 빠르게 적용하고 효율적으로 개발할 수 있는 방법론의 필요성 증가

특징

- 프로젝트의 요구사항은 기능 중심으로 정의
- 절차와 도구보다 개인과 소통을 중요하게 생각
- 작업 계획을 짧게 세워 요구 변화에 유연하고 신속하게 대응할 수 있음
- 소프트웨어가 잘 실행되는 데 가치를 둠
- 고객과의 피드백을 중요하게 생각함

애자일 선언문

- 공정과 도구보다 개인과 상호작용
- 계획을 따르기보다 변화에 대응하기
- 포괄적인 문서보다 동작하는 소프트웨어
- 계약 협상보다 고객과의 협력

유형

- **XP(eXtreme Programming)**
    - 의사소통 개선과 즉각적 피드백으로 소프트웨어 품질을 높이기 위한 방법론
    - 기존의 방법론에 비해 실용성을 강조한 방법론
    - 1~3주의 반복(Iteration) 개발 주기를 가지며, 5가지 가치와 12개의 실천 항목 존재
    - 5개의 가치
        - 용기: 용기를 가지고 자신감 있게 개발(코드를 작성하기 전에 테스트, 빠르게 피드백, 테스트에 부합하지 못하는 코드를 리팩토링할 수 있는용기)
        - 단순성: 필요한 것만 하고 그 이상의 것들은 하지 않음
        - 의사소통: 개발자, 관리자, 고객 간의 원활한 소통
        - 피드백: 의사소통에 대한 빠른 피드백
        - 존중: 팀원 간의 상호 존중
    - 12가지 기본 원리
        - 짝 프로그래밍(Pair Programming): 개발자 둘이서 짝으로 코딩하는 원리
        - 공동 코드 소유(Collective Ownership): 시스템에 있는 코드는 누구든지 언제라도 수정 가능하다는 원리
        - 지속적인 통합(CI; Continuous Integration): 매일 여러 번씩 소프트웨어를 통합하고 빌드해야 한다는 원리
        - 계획 세우기(Planning Process): 고객이 요구하는 비즈니스 가치를 정의하고, 개발자가 필요한 것은 무엇이며 어떤 부분에서 지연될 수 있는지를 알려주어야 한다는 원리
        - 작은 릴리즈(Small Release): 작은 시스템을 먼저 만들고, 짧은 단위로 업데이트한다는 원리
        - 메타포어(Metaphor): 공통적인 이름 체계와 시스템 서술서를 통해 고객과 개발자 간의 의사소통을 원활하게 한다는 원리
        - 간단한 디자인(Simple Design): 현재의 요구사항에 적합한 가장 단순한 시스템을 설계한다는 원리
        - 테스트 기반 개발(TDD; Test Driven Development): 작성해야 하는 프로그램에 대한 테스트를 먼저 수행하고 이 테스트를 통과할 수 있도록 실제 프로그램의 코드를 작성한다는 원리
        - 리팩토링(Refactoring): 프로그램의 기능을 바꾸지 않으면서 중복제거, 단순화 등을 위해 시스템 재구성을 한다는 원리
        - 40시간 작업(40-Hour Work): 개발자가 피곤으로 인해 실수하지 않도록 일주일에 40시간 이상을 일하지 말아야 한다는 원리
        - 고객 상주(On Site Customer): 개발자들의 질문에 즉각 대답해 줄 수 있는 고객을 프로젝트에 풀타임으로 상주시켜야 한다는 원리
        - 코드 표준(Coding Standard): 효과적인 공동 작업을 위해서는 모든 코드에 대한 코딩 표준을 정의해야 한다는 원리
- **스크럼(SCRUM)**
    - 매일 정해진 시간, 장소에서 짧은 시간의 개발을 하는 팀을 위한 프로젝트 관리 중심 방법론
    - 용어
        - 제품 책임자(Product Owner)
            - 이해관계자의 의견을 종합하여 제품에 대한 요구사항을 작성하는 주체
            - 주로 개발 의뢰자나 사용자가 담당
            - 이해관계자 중 개발될 제품에 대한 이해도가 높고 요구사항을 책임지고 의사 결정할 사람으로 선정
        - 제품 백로그(Product Backlog)
            - 제품과 프로젝트에 대한 요구사항
            - 스크럼 팀이 해결해야 하는 목록으로 소프트웨어 요구사항, 아키텍처 정의 등이 포함될 수 있음
        - 스프린트(Sprint)
            - 2~4주의 짧은 개발 기간으로 반복적 수행으로 개발품질 향상
        - 스크럼 미팅(Scrum Meeting)
            - 매일 15분 정도 미팅으로 To-Do List 계획수립
            - 데일리 미팅(Daily Meeting)이라고도 함
        - 스크럼 마스터(Scrum Master)
            - 프로젝트 리더. 스크럼 수행 시 문제를 인지 및 해결하는 사람
            - 스크럼 프로세스를 따르고, 팀이 스크럼을 효과적으로 활용할 수 있도록 보장하는 역할 등을 맡음
        - 스프린트 회고(Sprint Retrospective)
            - 스프린트 주기를 되돌아보며 정해놓은 규칙 준수 여부, 개선점 등을 확인 및 기록
            - 해당 스프린트가 끝난 시점이나 일정 주기로 시행
        - 번 다운 차트(Burn Down Chart)
            - 남아있는 백로그 대비 시간을 그래픽적으로 표현한 차트
            - 백로그는 보통 수직축에 위치하며 시간은 수평축에 위치
    - 스크럼에서 속도는 한 번의 스프린트에서 한 팀이 어느 정도의 제품 백로그를 감당할 수 있는지에 대한 추정치
- **린(Lean)**
    - 도요타의 린 시스템 품질기법을 소프트웨어 갭라 프로세스에 적용해서 낭비 요소를 제거하여 품질을 향상시킨 방법론
    - JIT(Just In Time), 칸반(Kanban) 보드를 사용함
    - 7가지 원칙
        - 낭비제거: 불필요한 코드나 기능과 같이 상품 가치에 영향을 미치지 않는 모든 것을 제거
        - 품질 내재화: TDD를 통해 코드의 실수를 방지
        - 지식 창출: 개발 과정 진행 중 참여자(기획자, 개발자, 고객 등) 학습의 필요성 존재
        - 늦은 확정: 중요한 문제에 대한 의사 결정을 최대한 미루고 요구사항 변경에 대응
        - 빠른 인도: 결과물을 가능한 한 빨리 제공. 사용자의 불확실성이 감소하고, 개발자에게는 결함발견의 기회가 주어짐
        - 사람 존중: 상호 간 책임의식과 신뢰 확보
        - 전체 최적화: 사용자 요구사항 수집부터 배포까지 모든 프로세스 최적화
- 크리스탈(Crystal)
    - 일반적으로 프로세스나 도구보다는 사람에게 더 많은 중점을 두는 방법론
    - 생명이 중요하지 않은 시스템에서 작업하는 최대 6명 또는 8명의 공동 배치 소프트웨어 개발자 팀에 적용
- ASD(Adaptive Software Development)
    - 개발을 혼란 자체로 규정하고, 혼란을 대전제로 그에 적응할 수 있는 소프트웨어 방법을 제시하기 위해 만들어진 방법론
    - 합동 어플리케이션 개발(Joint Application Development)을 사용함
- FDD(Feature Driven Development)
    - 개발을 상품이나 서비스 단위가 아니라 신규 기능 단위로 하는 개발 방법론