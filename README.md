# MS_Engage22_FaceRecognition
This is my submission for Microsoft Engage 2022, challenge taken is Challenge 1: Face Recognition.

Video Demo: https://youtu.be/FTha1SHbD44 <br/>
Click [here](https://drive.google.com/file/d/1zYGNFgYV_VYJas8NosinSNr2WfUqzuDG/view?usp=sharing) to know more about the Web-App 

## How to Run the Web-App

1. Clone the GitHub Repository at the required location. 
2. Install Anaconda from [here](https://www.anaconda.com/products/distribution)
3. Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required dependencies 
4. Install and create a virtual environment (in Anaconda Terminal) using: (Recommended)
```zsh
pip install virtualenv
virtualenv env_name
```
5. Activate the virtual environment (in Anaconda Terminal) using:
```zsh
.\env_name\Scripts\activate 
```
6. Installation:
```zsh
pip install -r requirements.txt 
pip install flask flask_sqlalchemy flask_login flask_bcrypt flask_wtf wtforms email_validator
```
7. Run command ((in Anaconda Terminal) inside the virtual environment:
```zsh
python app.py
```
## Credentials

Username: demo123 <br/>
Password: fakepass123

## Note
To exit the Live Feed of web camera press 'q'.
