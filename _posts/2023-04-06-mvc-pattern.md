---
layout: post
title: MVC 패턴
subtitle: 
categories: Spring
tags: [spring]
---
## **MVC 구조 및 패턴**

![MVC 패턴](/assets/images/mvc.png)


- ***⭐* MVC*⭐***  : *Model + View + Controller*
    - **Model** : 데이터를 담당하며, ***비즈니스 로직***을 처리하는 역할을 한다. 
    - **View** : 사용자 인터페이스를 담당한다. *(UI를 구현함)*
    - **Controller** : *Model과 View를 연결하는 역할을 한다. 사용자의 요청을 받아 해당 요청에 대한 처리를 수행하고, 모델에서 데이터를 가져와 View에 전달한다.*
<br>
<br>
- Model과 View는 서로 독립적이기 때문에 Model에서 View로 데이터를 보내는 것이 가능하나 Model과 View의 결합도를 높이고, 코드의 유지•보수성이 떨어지므로 Controller를 통해 전달하는 것을 권장한다.
- **MVC 패턴**을 사용하면 Model과 View가 다른 **Component**(*재사용이 가능한 독립적인 모듈*)들에 종속되지 않아 변경에 유리하다는 장점을 가질 수 있다.