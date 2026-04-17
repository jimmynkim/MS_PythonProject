# MS_PythonProject

> AI18기 파이썬 프로젝트 — Python 데이터 처리 언어 활용 역량 실습 저장소

---

## 개요

본 저장소는 데이터사이언스 핵심 언어인 **Python**의 기초 문법부터 실전 데이터 분석까지 단계적으로 학습하고 구현한 결과물을 담고 있습니다.  
`basic` 폴더에는 Python 핵심 문법 실습 코드가, `project` 폴더에는 Pandas·NumPy를 활용한 데이터 분석 프로젝트가 포함되어 있습니다.

---

## 저장소 구조

```
MS_PythonProject/
├── basic/                  # Python 기초 문법 실습
├── project/                # Python 기초 데이터 분석 프로젝트
├── data/                   # 실습용 데이터 파일
├── mymodule.py             # 커스텀 모듈 (재사용 함수 정의)
├── challenge.ipynb         # 종합 챌린지 노트북
├── turtle_test.py          # turtle 라이브러리 시각화 실습
└── heroes.csv              # 데이터 분석 실습용 CSV 데이터셋
```

---

## 주요 구현 내용

### 1. Python 기초 문법 실습 (`basic/`)

| 주제 | 주요 내용 |
|------|-----------|
| 변수 및 자료형 | int, float, str, bool, list, dict, tuple, set |
| 조건문 | if / elif / else 구조, 중첩 조건문 |
| 반복문 | for / while, break / continue, range() 활용 |
| 함수 | 함수 정의, 매개변수, 반환값, 기본값 인자 |
| 문자열 처리 | 슬라이싱, split/join, format, 정규식 기초 |
| 리스트 인덱싱 | 인덱싱, 슬라이싱, 리스트 컴프리헨션 |
| 파일 입출력 | open/read/write, with문, CSV 파일 처리 |

### 2. 실전 문제 해결 코드

- **한국 나이/만 나이 계산기**: 입력 생년월일 기반 현재 연령 계산 로직 구현
- **성적 등급 출력**: 점수 구간별 A~F 등급 판별 함수
- **월급 기반 세전/세후 연봉 계산**: 세율 적용 급여 계산 프로그램
- **버스 요금 계산기**: 나이/조건별 분기 처리 (성인/청소년/어린이/무료)
- **가위바위보 게임**: 랜덤 모듈 활용 대전 게임 구현
- **구구단 출력, 범위 내 짝수·중앙값 판별**: 반복문 응용
- **방명록 문자열 파싱, 잘못된 전화번호 검출**: 정규식 및 문자열 처리
- **영업 사원 실적 분석**: NumPy 평균 계산, 내림차순 정렬, 조건별 보너스/면담 대상 분류
- **두 왕조 이름 교집합 파악**: 집합(set) 연산 활용

### 3. 커스텀 모듈 (`mymodule.py`)

반복적으로 사용되는 함수를 별도 모듈로 분리하여 코드 재사용성 확보.

```python
# 예시: mymodule.py 내 함수 구조
import mymodule

result = mymodule.calculate_age(birth_year)
```

### 4. 데이터 분석 프로젝트 (`project/`, `challenge.ipynb`)

- **heroes.csv** 데이터셋 로딩 및 탐색적 데이터 분석(EDA)
- Pandas를 활용한 데이터 필터링, 집계, 정렬
- NumPy를 활용한 수치 연산 및 통계 처리
- Jupyter Notebook 기반 분석 결과 문서화 (재현 가능한 형식)

---

## 사용 기술

| 분류 | 기술 |
|------|------|
| 언어 | Python 3.x |
| 데이터 분석 | Pandas, NumPy |
| 시각화 | turtle (기초 그래픽) |
| 개발 환경 | Jupyter Notebook, VS Code |

---

## 실행 방법

```bash
# 기초 실습 파일 실행
python basic/<파일명>.py

# 커스텀 모듈 사용 예시
python -c "import mymodule; print(mymodule.<함수명>())"

# Jupyter Notebook 실행
jupyter notebook challenge.ipynb
```

---

## 학습 목표 달성 사항

- [x] Python 핵심 문법(조건문, 반복문, 함수, 자료구조) 이해 및 코드 구현
- [x] 문자열 파싱, 파일 입출력, 모듈화 실습
- [x] Pandas / NumPy를 활용한 실전 데이터 처리 및 분석
- [x] Jupyter Notebook을 통한 재현 가능한 분석 결과 문서화
