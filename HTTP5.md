# HTML5

```diff
- HTML5란?
+ HTML5란 무엇인지, 어떤 문법 체계를 갖는지 찾아볼 것
+ !DOCTYPE html, head, body 등

- 기본적인 태그
+ HTML5에서 사용하는 기본적인 태그에 대해서 찾아볼 것
+ p, span, div, form, input, button, a, i, svg 등등 찾아 볼 것

- 시맨틱 태그(semantic tag)
+ 시맨틱 태그란 무엇인지, 어떻게 사용하는지에 대해 찾아볼 것
+ header, nav, aside, main, article, figure, p, section, footer

- HTML DOM
+ HTML DOM이 무엇인지에 대해서 간단히 알아보기만 하기

- class 속성 vs id 속성
+ 따로 찾아봐도 안나올 것 같아 설명 추가
+ class는 보통 css에 사용, id는 javascript에 사용
+ 아래 코드 예시
```

```html
<style>
  /* css에서 class 이름을 통해서 접근 */
  .test-icon {
    background-color: black;
  }
</style>

<div class="test-icon" />
```

```html
<script>
  // javascript에서 id를 통해서 접근
  const testValue = document.querySelector("#testValue");
  const button = document.querySelector("#button");
  button.addEventListener("click", () => {
    let currnetValue = parseInt(testValue.innerText, 10) || 0;
    testValue.innerText = currentValue + 1;
  });
</script>
<div>
  <span>현재 값: </span>
  <span id="testValue">0</span>
  <button id="button">값 증가</button>
</div>
```
