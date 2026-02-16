# python

고수준 범용 프로그래밍 언어 (1991~)

## 장/단점

1. 장점

- 간결/직관적 문법
- 개발 속도 ↑
- 라이브러리 多
- AI/데이터 분야 표준
- cross platform
- OOP지원
- 명령형
- 함수형
...

2. 단점

- 느린 속도
- 모바일 네이티브에 약함
- 대규모 프로젝트에서 구조 관리 어려움(동적 타입 - Runtime Error발생 가능)
- 타입 안정성 ↓ (type hint등으로 보완)

## 용도

- 웹개발: Django, Flask 등의 프레임워크 사용해 웹앱 개발 가능
- 데이터 사이언스: NumPy, Pandas, Matplotlib, Scikit-learn 등의 라이브러리 사용해 데이터 분석/기계학습
- AI/기계학습: TensorFlow, PyTorch, Keras  등의 라이브러리
- 자동화(scripting): 반복 작업 자동화, 서버 관리, 트스트 자동화에 사용
- 과학 계산 및 시뮬레이션
...

## LLM 개발에 Python사용하는 이유

- AI와 기계 학습 라이브러리가 충실

Python은 TensorFlow 및 PyTorch와 같은 강력한 라이브러리를 사용해 AI 및 기계 학습 모델 구축 가능
OpenAI와 같은 API를 사용해 언어 모델 쉽게 사용

- 빠른 프로토타입 생성

개발속도 빠름 → 앱 아이디어를 즉시 형태로 만들 수 있음.
LLM 앱 개발은 아이디어를 시도/개선 프로세스가 많음 (Python의 유연성이 도움)

- 웹 앱과 API 쉽게 생성 가능

LLM 앱 만들 때 모델을 사용해 텍스트 생성, 질문 답변 기능을 API로 게시하는 경우가 많음.
Python에는 Flask및 FastAPI와 같은 가볍고 강력한 웹 프레임워크가 있어서 쉽게 웹앱과 API를 구축 가능.

- 우수한 데이터 처리

LLM 앱은 대량의 데이터를 다룸.
Python의 Pandas 및 NumPy와 같은 라이브러리는 데이터 전처리 및 분석에 뛰어남. → 데이터를 효율적으로 관리/조작 가능

- AI 분야의 표준 언어

AI와 LLM 관련 최신 기술이 python에서 제공.
많은 학술 논물, 샘플 코드가 python으로 작성됨. → 최신 기술에 쉽게 엑세스

## 실행 방법

- REPL 사용

REPL(Read-Eval-Print Loop): 대화형 Python 실행 환경

터미널/CMD에서 **python** 로 소스코드를 한 줄씩 입력해 실행.

장점: 짧은 코드 및 실험 테스트

단점: 코드 길어지면 사용 난해

```
Python 3.14.3 (main, Feb  3 2026, 15:32:20) [Clang 17.0.0 (clang-1700.6.3.2)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print("hello world!")
hello world!
>>> exit(
... )
```

- 노트북 사용
    - 노트북: 코드를 셀 단위로 작성 가능 → 실행결과 즉시 확인 가능
    - markdown과 함께 사용해 의견/설명 삽입 가능
    - 데이터 분석, 기계 학습 및 data science 프로젝트에 적합

- .py파일 만들기

python코드 저장 표준

```
ekim@lymGRHKVF33VX lesson1 % python test.py 
3
```

## python 학습 정리

| #  | 수업 이름 |
|----|-----------|
| 0  | 사전 준비 |
| 1  | 이 코스에서 배우는 것 |
| 2  | 파이썬의 기초 |
| 3  | 데이터 구조 및 파일 조작 |
| 4  | 함수 및 모듈 |
| 5  | 객체 지향 프로그래밍 |
| 6  | 파이썬 프로그램 테스트 |
| 7  | 인터넷 통신과 웹 앱의 작동 방식 |
| 8  | HTML과 CSS의 기초 |
| 9  | Flask로 웹 앱을 구축합시다. |
| 10 | 기본 LLM 프로그래밍: OpenAI API 사용법 |
| 11 | OpenAI 도구 호출: 웹 검색 등과의 연동 |
| 12 | LLM을 활용한 Excel 작업 자동화 |
| 13 | LLM을 활용한 웹 스크래핑 |
| 14 | RAG: 고유 데이터를 기반으로 답변 생성 |
| 15 | LangChain 및 에이전트 |
| 16 | 연습: LangChain과 Flask로 만드는 LLM 웹 앱 |
| 17 | 부록: 웹 앱 배포 |

