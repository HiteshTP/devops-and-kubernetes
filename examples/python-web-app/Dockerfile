FROM python:3
WORKDIR /usr/src/app
COPY requirements.txt ./
COPY devops ./
RUN pip install -r requirements.txt
COPY . .
EXPOSE 8000
ENTRYPOINT ["python3", "manage.py", "runserver", "0.0.0.0:8000"]


