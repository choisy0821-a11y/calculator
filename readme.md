# Streamlit 간단한 계산기 (Simple Calculator)

Streamlit을 활용하여 구현한 간단한 웹 기반 계산기 애플리케이션입니다. 두 개의 정수와 연산자를 입력받아 결과를 출력합니다.

---

## 📌 주요 기능
- **정수 입력**: 첫 번째 정수와 두 번째 정수를 입력받습니다.
- **사칙연산 지원**: `+`, `-`, `*`, `/` 연산을 지원합니다.
- **예외 처리 및 오류 메시지**:
  - 정수가 아닌 값이 입력된 경우 오류 메시지 출력
  - 허용되지 않은 연산자 기호가 입력된 경우 오류 메시지 출력
  - `0`으로 나눌 때 발생하는 예외 처리 (`ZeroDivisionError` 방지)

---

## 🛠️ 설치 및 실행 방법

### 1. 가상환경 생성 및 활성화 (선택 사항)
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

### 2. 패키지 설치
```bash
pip install -r requirements.txt
```

### 3. Streamlit 앱 실행
```bash
streamlit run app.py
```

---

## 📂 프로젝트 구조
```
├── app.py           # Streamlit 계산기 메인 코드
├── requirements.txt # 의존성 라이브러리 목록
└── README.md        # 프로젝트 설명 문서
```