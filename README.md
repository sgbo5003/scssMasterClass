# SCSS Masterclass

(S)CSS Layout Masterclass: Flexbox & Grid

## #3 SCSS
-------------

### #3.1 Variables and Nesting

> Variable
> 
- 파일명에 _붙이기
    - 파일 생성시 CSS로 변환되지 않는 것을 원하는 파일들은 파일명 맨 앞에 _를 붙인다.
    - ex) _variables.scss

> Nesting
> 

```css
.box {
  margin-top: 20px;
  &:hover { /* Nesting */
    background-color: green;
  }
  h2 { /* Nesting */
    color: blue;
    &:hover { /* Nesting */
      color: red;
    }
  }
  button { /* Nesting */
    color: red;
  }
}
```

- 부모 내 자식 요소들의 css를 굳이 class를 주지 않아도 된다.



