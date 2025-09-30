# SOLID란?

클린 코드로 유명한 로버트 마틴의 좋은 객체 지향 설계의 5가지 원칙을 SOLID라고 합니다.

SOLID의 5가지 원칙은 다음과 같습니다. 간단한 예시와 함께 설명드리겠습니다

## 단일 책임 원칙 (Single Responsibility Principle)

> "하나의 클래스는 하나의 책임만 가진다"

예) 젓가락은 젓가락, 숟가락은 숟가락의 역할에 집중해야한다.

## 개방-폐쇄 원칙 (Open/Closed Principle)

> "확장에는 열려 있으나, 변경에는 닫혀 있어야 한다"

예) 청소기 앞의 Head를 기능에 맞게 교체해서 사용 (입구가 넓은 Head, 입구가 좁은 Head)

## 리스코프 치환 원칙 (Liskov Substitution Principle)

> "프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 한다"

예) MacBook은 노트북에 상속

## 인터페이스 분리 원칙 (Interface Segregation Principle)

> "인터페이스 여러 개가 범용 인터페이스 하나보다 낫다"

예) 모니터 전원 공급장치, iPhone 전원 공급 장치

## 의존관계 역전 원칙 (Dependency Inversion Principle)

> "추상화에 의존하고, 구체화에 의존하지 않는다"

예) 개발자는 Windows에만 집중하는 것이 아닌 Operating System에 집중해야한다.

위 SOLID를 다시 읽고 정리하면서 좋은 개발, 좋은 개발자에 대해 다시 생각하게 됩니다.

기본적인 기능과 원칙이 잘 세워져 있어야 한 걸음 더 나아갈 수 있는 것 같습니다.
