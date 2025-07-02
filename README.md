# face_mask_detect_major
Create a virtual env using venv:
python -m venv env

activate the enviorment
env\Scripts\activate

install required packages
pip install -r face_mask_detect_major-master/requirements.txt

Create training model
python mask_detector_model.py

run 
python detect_mask_video.py
