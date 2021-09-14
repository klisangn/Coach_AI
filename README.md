# Data analysis
- Document here the project: Coach_AI
- Description: 2-week project as part of "Le Wagon - Data Science bootcamp": web-app for personalized physical exercise recognition, counting and feedbacks.
- Data Source: UCF 101 Dataset
- Type of analysis: MediaPipe Pose, Machine Learning (SVC)
- Deployment: Fast API, Uvicorn, Streamlit-webrtc
- Deployed web-app : https://share.streamlit.io/sebrod93/coachaiwebsite/app.py
# Install
Go to `https://github.com/{group}/Coach_AI` to see the project, manage issues,
setup you ssh public key, ...
Create a python3 virtualenv and activate it:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```
Clone the project and install it:
```bash
git clone git@github.com:{group}/Coach_AI.git
cd Coach_AI
pip install -r requirements.txt
make clean install
