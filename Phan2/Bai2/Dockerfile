FROM python:3.9

WORKDIR /app

# Sao chép file requirements.txt vào container
COPY requirements.txt requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 5000

CMD ["python", "app.py"]
