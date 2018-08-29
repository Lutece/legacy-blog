---
title: HTML5 Form Validation에 대하여
categories: Html
---

Form 태그는 유저가 자신의 데이터를 기반으로 웹 페이지와 상호작용하는 과정에서 사용되는 마크업 태그입니다. 여기서 상호작용이란 Form Control 요소들을 통해 입력받은 데이터를 전달하거나, 입력된 데이터가 있는지 확인하거나, 입력된 데이터에 관하여 문제가 발생했을 때 유저에게 직관적으로 이해시킬 수 있도록 조치를 취하는 등의 일들을 말합니다. 이 글에서는 Form Control 요소들에 입력된 데이터의 유효성 검사 기능을 담당하는 HTML5 API와 유효성 검사의 결과를 나타내는 CSS 가상 선택자, 한글 입력과 관련된 여러가지 이슈들에 대해 알아보도록 하겠습니다.

<!-- more -->
---

### HTML5 API와 프로퍼티

HTML5 API와 유효성 검사를 위해 제공되는 프로퍼티들은 브라우저 내에 내장된 기능이기 때문에 **읽기 전용**이라는 상태를 갖습니다. Form control 요소들은 유효성 검사 결과에 대한 여러가지 값들을 **validity**라는 프로퍼티 내에 담고 있으며 유효성 검사와 관련된 몇 가지 메서드들도 함께 갖고 있습니다.

```javascript
interface ValidityState {
  readonly attribute boolean valueMissing;
  readonly attribute boolean typeMismatch;
  readonly attribute boolean patternMismatch;
  readonly attribute boolean tooLong;
  readonly attribute boolean tooShort;
  readonly attribute boolean rangeUnderflow;
  readonly attribute boolean rangeOverflow;
  readonly attribute boolean stepMismatch;
  readonly attribute boolean badInput;
  readonly attribute boolean customError;
  readonly attribute boolean valid;
};
```
[위 정보는 **validity** 프로퍼티가 갖고 있는 여러가지 상태 값에 대한 명세를 나타냅니다.](https://www.w3.org/TR/html5/sec-forms.html#validitystate)




---

# CSS 가상 선택자

# Form 태그와 인코딩

Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.

## 데이터 통신과 Form 태그

Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.
**Form 태그의 순서도**
**Form 태그는 어떻게 데이터를 다루는가**

## Form Validation의 정의
Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.

## Form Validation 다루기
Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.Minos is a simple and retro styled Hexo theme which concentrates more on your ideas. Minos is very expressive as it has extensive plugin support, colorful code highlighting choices, flexible configurations and out-of-box multi-language support. Meanwhile, minimalism also makes Minos a great theme for both writers and readers who desire a better reading experience.

- HTML5 API

- Attribute

- CSS

- Element

- 사용자 경험을 위한 몇 가지 팁
