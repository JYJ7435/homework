# 마크다운 문법

# 제목 (Heading)

- #을 사용해 `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>` 태그로 변환되는 '제목(Header)'을 표현

- 예시

```markdown
# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5
```

# 강조

- 각각 `<em>(기울임), <strong>(두꺼움), <del>(취소선)` 태그로 변환되는 '강조(Emphasis)'를 표현
- 마크다운에서 지원하지 않는 밑줄을 추가하려면, `<u></u>`(밑줄) 태그를 직접 사용

- 예시

```markdown
**굵게**
_기울임_
**_굵은 기울임_**
```

# 목록

- `<ol>, <ul>, <li>` 태그로 변환되는 '목록(List)'을 표현
- `1.` 로 시작하는 항목을 작성하면 `<ol>`로 변환되며, `-`로 시작하는 항목을 작성하면 `<ul>`로 변환

- 예시

```markdown
1. 순서가 있는 항목
1. 순서가 있는 항목

- 순서가 없는 항목
- 순서가 없는 항목
```

# 링크

- `<a>`로 변환되는 '링크(Links)'를 표현

- 예시

```markdown
[이름](링크)
[이름](링크 '설명')
```

# 이미지

- `<img>`로 변환되는 '이미지(Images)'를 표현
- 링크과 비슷하지만, 앞에 `!`를 추가

- 예시

```markdown
![대체텍스트](이미지주소)
![대체텍스트](이미지주소 '설명')
![대체텍스트][참조]
```

# 코드 강조, 인라인

- `<pre>, <code>` 태그로 변환되는 '코드(Code)'를 표현, `` `(백틱)``기호를 사용
- 강조할 코드를 `` `(백틱) `` 기호로 감싸 '인라인(InLine)' 코드를 표현

-예시

```markdown
`코드` 강조
```

# 블록

- `` ` ``를 3번 이상 입력하고 언어(코드) 이름을 명시해, 코드 '블록(Block)'를 표현

- 예시

````markdown
```언어이름
내용
```
````

# 표

- `<table>` 태그로 변환되는 '표(Table)'를 표현
- 테이블 헤더를 구분하기 위해, 3개 이상의 `-(hyphen/dash)` 기호를 사용
- 테이블 헤더를 구분하며 `:(Colons)` 기호를 추가해 셀(열/칸) 안에 내용을 정렬할 수 있다.

  - `---`, `:---` : 좌측 정렬
  - `:---:` : 가운데 정렬
  - `---:` : 우측 정렬
  - 가장 좌측과 가장 우측에 있는 `|(vertical bar)` 기호는 생략 가능

- 예시

```markdown
| 헤더 | 헤더 | 헤더 |
| ---- | ---- | ---- |
| 셀   | 셀   | 셀   |
| 셀   | 셀   | 셀   |

| 헤더 | 헤더 | 헤더 |
| ---- | ---- | ---- |
| 셀   | 셀   | 셀   |
| 셀   | 셀   | 셀   |
```

# 인용문

- `<blockquote>` 태그로 변환되는 '인용문(BlockQuote)'을 표현
- 줄바꿈(Line Breaks)을 위해서는 문장 마지막에서 `<br>` 태그를 직접 입력하거나, 문장 마지막에서 `띄어쓰기를 2번` 이상 입력

```markdown
> 인용문
>
> > 중첩된 인용문(nested blockquote)
> >
> > > 중중첩 인용문 1<br>
> > > 중중첩 인용문 2<br>
> > > 중중첩 인용문 3
```

# 수평선

- `---`, `___`, `***` 각 기호를 3개 이상 입력해, `<hr>` 태그로 변환되는 '수평선(Horizontal Rule)'을 표현

- 예시

```markdown
---

---

---
```

# 주석

- `<!-- -->`, `[//]: #` 기호를 사용해, 주석(Comment)을 표현

- 예시

```markdown
<!-- 안녕하세요. -->

[//]: # '안녕하세요.'
[//]: # '안녕하세요.'
[//]: # '안녕하세요.'
```
