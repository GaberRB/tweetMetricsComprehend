FROM python:3.9
WORKDIR /app

COPY tweetApi/app/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY tweetApi/app .

CMD ["python", "main.py"]