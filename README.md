# javascript-calculator-precourse

## 구현목록

---

### 입력

---

- 사용자가 입력한 문자열을 반환

### 입력값 검수

---

- 입력된 문자열을 검수  
  1. 커스텀 구분자의 존재 유무
      - 커스텀 구분자의 유효성 검사
  2. 구분자(기본, 커스텀)를 기준으로 입력값을 문자열 -> 배열로 변환
  3. 배열로 변환된 입력값의 유효성 검사
      - 문자열 -> 숫자로 변환이 가능한 입력값인지
      - 구분자(기본, 커스텀) 이외의 구분자의 존재 유무
  4. 유효성을 통과한 변환값을 반환

### 입력값 변환

---
1. 문자열을 배열로 변환  
    1. 기본 구분자 (, / :)를 사용해서 변환
    2. 커스텀 구분자를 사용해서 변환
2. 배열 내의 요소를 문자열 -> 숫자로 변환


### 입력값 계산

---

변환된 입력값을 덧셈으로 계산하여 결과값을 반환


### 에러 처리

---

1. 커스텀 구분자의 유효성
2. 입력값의 유효성  

## Commit Message

---

- feat
- fix
- docs
- style
- refactor
- test
- chore

## 추가적인 학습 목록

[Markdown](https://github.com/thumbthing/javascript-calculator-7/blob/thumbthing/study/markdown.md)

[vscode](../study/vscode.md)

[Git](https://github.com/thumbthing/javascript-calculator-7/blob/thumbthing/study/git.md)

[JavaScript](https://github.com/thumbthing/javascript-calculator-7/blob/thumbthing/study/javascript.md)

[프리코스 회고록](https://github.com/thumbthing/javascript-calculator-7/blob/thumbthing/study/retrospective.md)