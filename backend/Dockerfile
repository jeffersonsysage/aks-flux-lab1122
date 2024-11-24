FROM python:3.9-slim
WORKDIR /app
COPY app.py .
# 安裝所需的 Python 套件
RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "app.py"]
