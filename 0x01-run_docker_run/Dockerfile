FROM python:3.11-slim

# set the container to listen to port 8000
EXPOSE 8000

# set working directory
WORKDIR /home/app

# copy contents of hyper-app to working directory
ADD /hyper-app .

# install requirements
RUN pip install -r requirements.txt

ENTRYPOINT ["python3", "main.py"]


