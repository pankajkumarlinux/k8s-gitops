FROM python:3.11-slim
WORKDIR /app
COPY web-app/requirements.txt .
RUN pip install -r requirements.txt
COPY web-app/app.py .
CMD ["python", "app.py"]