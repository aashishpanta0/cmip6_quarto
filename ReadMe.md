# Instructions

Install Quarto
- https://quarto.org/docs/get-started/


```bash

c:\Python310\python.exe -m venv .venv
.venv\Scripts\activate
python -c "import sys;print(sys.executable)"

SET PATH=%PATH%;C:\Program Files\Quarto\bin
SET QUARTO_PYTHON=c:\python310\python.exe

quarto check jupyter
quarto preview


```