# PDF to Text Converter

## Yêu cầu
- Python 3.9+
- Tesseract OCR: Tải từ https://github.com/UB-Mannheim/tesseract/wiki
- Poppler: Tải từ https://github.com/oschwartz10612/poppler-windows/releases
- Thư viện Python: Cài từ requirements.txt

## Cài đặt
1. Kích hoạt môi trường ảo (nếu tương thích):
```bash
venv\Scripts\activate # Windows source
venv/bin/activate # Linux/Mac
```
2. Nếu venv không tương thích, tạo mới:
```bash
python -m venv venv
venv\Scripts\activate
```
---

- File requirements.txt:
```txt
alabaster==1.0.0
anyio==4.9.0
arrow==1.3.0
attrs==25.3.0
babel==2.17.0
beautifulsoup4==4.13.4
bibtexparser==1.4.3
certifi==2025.4.26
cffi==1.17.1
charset-normalizer==3.4.2
colorama==0.4.6
cryptography==45.0.4
Deprecated==1.2.18
docutils==0.21.2
fake-useragent==2.2.0
feedparser==6.0.11
free_proxy==1.1.3
h11==0.16.0
httpcore==1.0.9
httpx==0.28.1
idna==3.10
imagesize==1.4.1
Jinja2==3.1.6
lxml==5.4.0
MarkupSafe==3.0.2
numpy==2.3.0
outcome==1.3.0.post0
packaging==25.0
pandas==2.3.0
pdf2image==1.17.0
pdfminer.six==20250506
pdfplumber==0.11.7
pillow==11.2.1
pycparser==2.22
Pygments==2.19.1
pyparsing==3.2.3
PyPDF2==3.0.1
pypdfium2==4.30.1
PySocks==1.7.1
pytesseract==0.3.13
python-dateutil==2.9.0.post0
python-docx==1.1.2
python-dotenv==1.1.0
python-json-logger==3.3.0
pytz==2025.2
requests==2.32.4
roman-numerals-py==3.1.0
scholarly==1.7.11
selenium==4.33.0
sgmllib3k==1.0.0
six==1.17.0
sniffio==1.3.1
snowballstemmer==3.0.1
sortedcontainers==2.4.0
soupsieve==2.7
Sphinx==8.2.3
sphinx-rtd-theme==3.0.2
sphinxcontrib-applehelp==2.0.0
sphinxcontrib-devhelp==2.0.0
sphinxcontrib-htmlhelp==2.1.0
sphinxcontrib-jquery==4.1
sphinxcontrib-jsmath==1.0.1
sphinxcontrib-qthelp==2.0.0
sphinxcontrib-serializinghtml==2.0.0
trio==0.30.0
trio-websocket==0.12.2
types-python-dateutil==2.9.0.20250516
typing_extensions==4.13.2
tzdata==2025.2
urllib3==2.4.0
websocket-client==1.8.0
wrapt==1.17.2
wsproto==1.2.0
```

- Chạy file requirements.txt
```py
pip install -r requirements.txt
```
3. Cài Tesseract và Poppler:
- Windows: Tải và thêm vào PATH.
- Linux: `sudo apt install tesseract-ocr tesseract-ocr-vie poppler-utils`
- Mac: `brew install tesseract poppler`

## Chạy code
`python pdf_converter.py`

---

Create by huynhkhuan | CT06PM | DHV
