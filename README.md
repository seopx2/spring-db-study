# spring-db-study
GDGoC Spring &amp; Database Study 실습 및 학습 기록

## Github 사용 방법

### 1. Repository Clone

스터디 Repository를 로컬에 clone합니다.

```bash
git clone https://github.com/seopx2/spring-db-study.git
cd spring-db-study
```
> `git clone`은 Repository를 처음 연결할 때 한 번만 실행합니다.


### 2. 본인 폴더에서 작업

본인 이름의 폴더 안에서 주차별 실습 코드를 작성합니다.

```text
본인 이름/
└── week01/
    ├── practice/
    └── assignment/
```
> **본인 이름의 폴더에서만 작업해주세요.**
> 
> ⚠️ 다른 팀원의 폴더는 수정하지 않습니다.


### 3. 작업 전 최신 내용 가져오기

작업을 시작하기 전에 Repository의 최신 내용을 가져옵니다.

```bash
git pull
```


### 4. 작업 내용 업로드

실습 또는 과제 작성을 완료한 후 변경사항을 업로드합니다.

```bash
git add .
git commit -m "week01: add practice"
git push
```


### 5. 기본 작업 순서

```text
git pull
   ↓
실습 및 과제 작성
   ↓
git add .
   ↓
git commit
   ↓
git push
```


### Commit Message

Commit Message는 다음 형식을 사용합니다.

```text
week01: add practice
week01: add assignment
week02: add practice
week02: add assignment
주차와 작업 내용을 간단하게 작성해주세요.
```


### 📂 Repository Structure

```text
spring-db-study/
├── README.md
├── materials/
│
├── 멤버A/
│   └── week01/
│       ├── practice/
│       └── assignment/
│
├── 멤버B/
│   └── week01/
│       ├── practice/
│       └── assignment/
│
└── 멤버C/
    └── week01/
        ├── practice/
        └── assignment/
```

- materials/ : 스터디에서 공통으로 사용하는 실습 자료
- 개인 폴더/ : 각자의 실습 및 과제 코드
- practice/ : 강의별 실습 코드
- assignment/ : 주차별 과제
