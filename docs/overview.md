# What is HTML?

## HTML에 오신 것을 환영합니다!

HTML은 HyperText Markup Language의 약자입니다.

스크립트를 사용하여 기능을 수행하는 스크립팅 또는 프로그래밍 언어와 달리 마크 업 언어는 태그를 사용하여 내용을 식별합니다.

다음은 HTML 태그의 예입니다.

```html
<p> I'm a paragraph </p>
```

## 웹 구조

HTML을 사용하여 코드를 작성하는 기능은 모든 웹 전문가에게 필수적입니다. 

이 기술을 습득하는 것은 웹 콘텐츠를 만드는 방법을 배우는 모든 사람들을위한 출발점이되어야합니다.

**Modern Web Design**

HTML: Structure  
CSS: Presentation  
JavaScript: Behavior  

PHP or similar: Backend  
CMS: Content Management

# Basic HTML Document Structure

## &lt;HTML&gt; 태그

수년 동안 다양한 버전이 출시되었지만 HTML 기본 사항은 동일하게 유지됩니다.

HTML 문서의 구조는 샌드위치의 구조와 비교되었습니다. 샌드위치에는 두 개의 빵 조각이 있으므로 HTML 문서에는 여는 HTML 태그와 닫는 HTML 태그가 있습니다.

이러한 태그는 샌드위치의 빵과 마찬가지로 다른 모든 것을 둘러 쌉니다.

```html
<html>
...
</html>
```

> HTML 문서의 모든 내용은 &lt;html&gt; 태그로 둘러싸여 있습니다

## &lt;head&gt; 태그

HTML 태그 열기 바로 다음에 헤드 태그 열기 및 닫기로 식별되는 문서의 머리글을 찾을 수 있습니다.

HTML 파일의 헤드에는 페이지를 작동시키는 데 도움이되는 모든 비 시각적 요소가 포함되어 있습니다.

```html
<head>
...
</head>
```

> 헤드 섹션 요소는 나중에 논의 될 것입니다.

## &lt;body&gt; 태그

body 태그는 head 태그 다음에옵니다.
모든 시각적 구조 요소는 body 태그 내에 포함됩니다.

제목, 단락, 목록, 따옴표, 이미지 및 링크는 body 태그 내에 포함될 수있는 요소 중 일부일뿐입니다.

기본 HTML 구조 :

```html
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

> &lt;body&gt; 태그는 HTML 문서의 주요 내용을 정의합니다.

# Creating Your First HTML Page

## HTML 파일

HTML 파일은 텍스트 파일이므로 모든 텍스트 편집기를 사용하여 첫 번째 웹 페이지를 만들 수 있습니다.

아주 멋진 HTML 편집기가 있습니다. 당신은 당신을 위해 일하는 것을 고를 수 있습니다. 이제 예제를 메모장에 작성해 보겠습니다.

본문 섹션에 "This is a line of text"라는 텍스트 편집기에 기본 HTML 구조를 추가하십시오.

```html
<html>
  <head>
  </head>
  <body>
    This is a line of text. 
  </body>
</html>
```

예제에서 파일은 first.html로 저장됩니다.

파일을 열면 다음 결과가 웹 브라우저에 표시됩니다.

> 파일을 저장하는 것을 잊지 마십시오. HTML 파일 이름은 .html 또는 .htm로 끝나야합니다.

## &lt;title&gt;태그

웹 페이지를 설명하는 탭에 제목을 배치하려면 헤드 섹션에 &lt;title&gt; 요소를 추가하십시오.

```html
<html>
  <head>
    <title>first page</title>
  </head>
  <body>
    This is a line of text. 
  </body>
</html>
````

> 제목 요소는 페이지를 설명하고 검색 엔진에서 사용되기 때문에 중요합니다.

# 블로그 만들기

이 과정을 통해 우리는 자신 만의 고유 한 블로그 프로젝트를 연습하고 만들 수 있으므로 배운 내용을 그대로 사용하고 사용할 수있게됩니다. 

계속해서 **작업** 섹션의 지침을 따르십시오. 이것이 완성 된 블로그 페이지의 모습입니다.

> **작업** : 코드 및 출력을 보려면 직접 시도하십시오.

```html
<html>
  <head>
    <title>My Blog</title>
  </head>
    <body>
...
```

긴 코드를 두려워하지 마십시오. 코스를 마칠 때까지 모든 것이 완벽하게 이해 될 것이며, 고도로 행동 할 수 있습니다. 우리는 그것을 보장한다!

> **작업**:  
> 1. 코드를 엽니다.
> 2. 맨 위 머리글에서 이름을 자신의 이름으로 변경하십시오.
> 3. 페이지 제목을 변경하십시오. 페이지 제목은 페이지의 &lt;head&gt; 태그에있는 &lt;title&gt; 태그 안에 있습니다.