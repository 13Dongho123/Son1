
## 📝 README.md (설치부터 실행까지 풀 가이드)

```markdown
# 🚇 지하철/버스 실시간 환승 대시보드 (Flask)

> **공공데이터 API를 활용하여 실시간 대중교통 도착 정보를 통합 관리하는 대시보드입니다.**

---

## 🛠 1. 개발 환경 (Requirements)
* **언어**: Python 3.10 이상
* **프레임워크**: Flask 3.1.2
* **라이브러리**: requests, python-dotenv 등 (requirements.txt 참고)

---

## 📂 2. 프로젝트 구조 (Project Structure)
```text
.
├── app2.py              # Flask 메인 서버 코드
├── static/
│   └── style.css       # 웹 페이지 스타일 디자인
├── templates/
│   └── index2.html      # 사용자 검색 인터페이스
├── requirements.txt    # 필수 라이브러리 목록 (자동 설치용)
└── README.md           # 프로젝트 가이드

```

---

## ⚙️ 3. 설치 및 실행 방법 (Installation & Setup)

### STEP 1: 프로젝트 다운로드 (Clone)

```bash
git clone [https://github.com/13Dongho123/Song.git](https://github.com/13Dongho123/Song.git)
cd [폴더이름]

```

### STEP 2: 가상환경 생성 및 활성화

**Windows:**

```bash
python -m venv venv
.\venv\Scripts\activate

```

**Mac/Linux:**

```bash
python -m venv venv
source venv/bin/activate

```

### STEP 3: 필수 라이브러리 설치

```bash
pip install -r requirements.txt

```

### STEP 4: 서버 실행

```bash
python app.py

```

### STEP 5: 브라우저 접속

브라우저 주소창에 아래 주소를 입력합니다.

> **https://www.google.com/search?q=http://127.0.0.1:5000**

---

## ✨ 4. 주요 기능 (Key Features)

1. **지하철 정보**: 상/하행 실시간 도착 예정 시간 및 현재 위치 조회
2. **버스 정보**: 정류장별 노선 도착 예정 시간 및 잔여 좌석 확인
3. **이중 검색**: 한 화면 내에서 지하철과 버스 정보를 동시에 비교하여 환승 편의성 극대화

---
