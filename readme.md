# Tiny Secondhand Shopping Platform  

본 코드는 Flask, SocketIO, SQLite 등을 기반으로 동작하며,  
miniconda 환경에서 실행됩니다.

---

## Requirements

이 프로젝트는 Conda 가상환경을 기반으로 설정됩니다.  
아직 설치되어 있지 않다면 아래 링크에서 **Miniconda**를 설치하세요:

🔗 https://docs.anaconda.com/free/miniconda/index.html

### 설치 및 환경 설정

```bash
# 1. 프로젝트 클론
git clone https://github.com/lhywk/secure-coding.git
cd secure-coding

# 2. Conda 환경 생성
conda env create -f enviroments.yaml
conda activate secure-coding
```

### 서버 실행

```bash
python app.py
```

### 외부 접속 
외부 기기(모바일, 다른 PC 등)에서 접하려면 ngrok을 활용합니다.
```bash
# ngrok 설치 (Ubuntu 기준)
sudo snap install ngrok

# 로컬 5000번 포트를 외부에 노출
ngrok http 5000
```
