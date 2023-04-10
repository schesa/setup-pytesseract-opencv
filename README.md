# How to get started

cd Desktop  
mkdir schesa  
cd schesa  
python -m venv schesa_env  
source schesa_env/Scripts/activate  
pip install numpy  
pip install matplotlib  
pip install opencv-python  
python test.py  

# Digits recognition  
https://docs.opencv.org/3.4/d8/d4b/tutorial_py_knn_opencv.html  
https://github.com/opencv/opencv/tree/master/samples/data  

# OCR pytesseract 
pip install pytesseract  

FOR WINDOWS:  
 Install tesseract using windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki  
 Set the tesseract path in the script before calling image_to_string:  
	pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'  

python test-tesseract.py  

https://www.youtube.com/watch?v=VEpFyTyCH-I  
https://stackoverflow.com/questions/50951955/pytesseract-tesseractnotfound-error-tesseract-is-not-installed-or-its-not-i  
