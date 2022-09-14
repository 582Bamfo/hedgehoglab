



FROM python:3.8

WORKDIR /app

COPY requirements.txt ./
RUN pip3 install --upgrade pip 

COPY . .
EXPOSE 8000

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]