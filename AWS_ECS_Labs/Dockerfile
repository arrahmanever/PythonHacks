FROM python:3.12.3-alpine3.18

# WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

ENV PYTHONUNBUFFERED=1

CMD ["python" ,"app.py"]