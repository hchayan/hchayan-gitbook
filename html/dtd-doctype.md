# DTD와 DOCTYPE

### 1. DTD(Document Type declaration)

*   **작성한 html 코드가 어떤 방식의 html으로 작성되었는 선언** 하는 역할.

    > 세월에 따라 태그들의 의미들이 달라지게 되고 이 태그들이 어떤 표준을 따르는지 명시하는 방
* XML 문서의 구조, 법적 요소 및 속성을 정의한다.
* DOCTYPE은 이런 DTD 문법중 하나이다.



### 2. DOCTYPE 이란?

* Document Type의 약자이다.
* **DTD 를 선언하는 문법이다.**
* HTML 태그를 정의하기 전에 가장 먼저 선언되어야 한다.
* 미 선언시, 호환모드로 동작하게 되고 이는 각 브라우저 마다 문서가 나타나는 방식이 달라지게 된다.&#x20;



### 3. HTML5 이전의 DTD

```html
// HTML 4.01에서의 DTD
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" 
"http://www.w3.org/TR/html4/loose.dtd">

// XHTML 1.1에서의 DTD
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" 
"http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
```

* SGML(문서용 마크업 언어를 정의하기 위한 메타 언어) 기반으로 버전을 인식한다.



### 4. HTML5 DTD

```
// 현시점에선 HTML5의 DTD로 명시 권장
<!DOCTYPE html>  
```

* HTML5 부턴 더이상 SGML 기반으로 버전을 인식하지 않기에 DTD를 참조할 필요가 없다.
*   **doctype은 HTML 문법을 표준 모드로 실행하면 된다는 의미로 단일화 되었**. ([참조](https://www.w3.org/TR/html5-diff/#doctype))

