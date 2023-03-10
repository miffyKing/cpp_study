### 클래스와 구조체의 차이점

→ 접근과 관련해 별도의 선언을 하지 않으면, 클래스 내에 선언된 변수 및 함수에 대한 접근은 허용하지 않는다. 따라서 접근과 관련된 지시를 (접근 제어 지시자) 따로 내려주어야 한다. 라는것이 바로 클래스와 객체의 차이점이다.

### 접근제어 지시자

- **public**
    - 어디서든 접근 허용
- **protected**
    - 상속관계에 있을 때, 유도 클래스에서의 접근 허용
- **private**
    - 클래스 내에서만 접근 허용

클래스의 선언 : 헤더 파일에 저장해, 필요한 위치에 쉽게 포함될 수 있도록 한다.

클래스의 정의 : 소스 파일에 저장해, 컴파일 되도록 한다.

### 객체지향 프로그래밍의 이해

- 객체지향 프로그래밍은 현실에 존재하는 사물과 대상, 그리고 그에 따른 행동을 있는 그대로 실체화 시키는 형태의 프로그래밍.
- 객체는 하나 이상의 상태 정보와 하나 이상의 행동으로 구성됨.

클래스 기반의 두 가지 객체 생성 방법

- ClassName objName;     :  일반적인 변수의 선언 방식
- ClassName * ptrObj = new ClassName;    : 동적 할당방식 (힙 할당)

객체지향에서 어떠한 함수 호출을 통해 다른 객체들에게 메시지를 전달하는 방법을 메시지 전달 이라고 한다.