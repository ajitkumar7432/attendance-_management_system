
# Face based attendance system using python and OpenCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/) 

### What steps you have to follow?
- Download or clone the repository to your device
- run `pip install -r requirements.txt` in a command prompt or terminal
- Create a `TrainingImage` folder in the project root if it does not already exist
- Open `attendance.py` and `automaticAttedance.py`, then update the paths for your system
- Run `attendance.py`

### Project flow
- Register a student from the main window
- Capture images from the camera using the registration flow
- Train the model from the captured images
- Start attendance marking for a selected subject
- View the generated attendance records in table or CSV form

### Configuration
- Set your own database connection string with the `MONGODB_URI` environment variable before running the backend
- Update local file paths in the Python scripts if your folder layout is different


