1. create a virtual environment
python -m venv pythonDocker
pythonDocker\Scripts\activate
pip list
python -m pip install --upgrade pip


git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sporhaberleri94/pythonDocker.git
git push -u origin main

set DOCKER_HOST=tcp://localhost:2375 

2- install dependencies 
pip install uvicorn

3- pip freeze > requirements.txt