---
layout: post
title: MVC 패턴
subtitle: 
categories: Spring
tags: [MVC]
---
## **MVC 구조 및 패턴**

![MVC 패턴](/assets/images/mvc.png)


- ***⭐* MVC*⭐***  : *Model + View + Controller*
    - **Model** : 애플리케이션의 비즈니스 로직, 규칙 및 데이터와의 상호 작용을 관리한다. 이것은 단순한 데이터 저장소 역할뿐만 아니라, 데이터와 관련된 모든 연산과 규칙을 포함한다.
    - **View** : 사용자 인터페이스를 담당한다. 사용자에게 보여지는 UI 요소를 구현하며, 사용자의 데이터 표현 형태를 결정한다.
    - **Controller** : 사용자의 요청을 받아 그 요청을 해석하고, 적절한 Model 메소드를 호출하여 요청을 처리한다. 처리된 데이터나 결과를 View에 전달하여 사용자에게 응답을 제공한다. 이를 통해 Model과 View 사이의 연결 역할을 수행한다.

<br>
- Model과 View는 서로 독립적이므로 직접적인 데이터 전달 없이 서로에게 영향을 미치지 않는다. 이러한 구조 덕분에 MVC 패턴은 코드의 재사용성과 유지보수성을 향상시키며, 각 컴포넌트의 변경이 다른 컴포넌트에 큰 영향을 미치지 않도록 도와준다.

<br>

- [참고자료1](https://cloudstudying.kr/lectures/235)
- [참고자료2](https://carrotweb.tistory.com/216)