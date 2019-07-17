# OCR POC on govt id proofs


brew install tesseract

pip install scipy
pip install ftfy==4.4.3
pip install Pillow
pip install pytesseract
pip install opencv-python
pip install python-dateutil


Training directories can be found using brew list tesseract Possible location can be /usr/local/Cellar/tesseract/3.05.02/share/tessdata/

Option 1
python ocr_v2.py -i 1.jpeg

Option 2
python pan_card_detect.py 1.jpeg