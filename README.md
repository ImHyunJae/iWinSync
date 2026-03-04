# iWinSync 📸

**iWinSync**는 아이폰/아이패드의 사진을 Windows PC로 안전하고 스마트하게 백업하고 정리하는 데스크탑 애플리케이션입니다. 12년 차 엔지니어의 노하우를 담아 성능과 정확성에 집중했습니다.

## ✨ Key Features

* **Smart Backup:** 아이폰의 DCIM 폴더를 스캔하여 신규 사진만 골라냅니다.
* **High-Speed Hashing:** 파일 전체가 아닌 부분 해싱 알고리즘을 통해 대용량 사진도 빠르게 비교합니다.
* **Auto-Naming:** EXIF 데이터를 추출하여 `YYYYMMDD_HHMM_IMG.jpg` 형식으로 자동 정리합니다.
* **Deduplication:** 해시값과 파일 크기를 대조하여 중복된 사진을 찾아내고 저장 공간을 최적화합니다.
* **User Friendly UI:** PySide6 기반의 직관적인 대시보드와 멀티스레딩 처리로 멈춤 없는 사용자 경험을 제공합니다.

## 🛠 Tech Stack

* **Language:** Python 3.10+
* **Framework:** PySide6 (Qt for Python)
* **Database:** SQLite3 (Metadata & Hash management)
* **Libraries:** Pillow, openpyxl (optional), pathlib

## 🚀 Getting Started

### Prerequisites
- Windows 10 or 11
- iTunes installed (for iPhone MTP connection)

### Installation
1. Clone the repository
   ```bash
   git clone [https://github.com/YourUsername/iWinSync.git](https://github.com/YourUsername/iWinSync.git)
Install dependencies

Bash
pip install -r requirements.txt
Run the application

Bash
python main.py
Developed by [Hyunjae] | Part of the DevScene Project.
