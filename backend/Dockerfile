# 使用 Python 作為基礎映像
FROM python:3.9-slim

# 設定工作目錄
WORKDIR /app

# 複製程式碼和依賴文件到容器
COPY app.py .
COPY requirements.txt .

# 安裝 Python 依賴
RUN pip install --no-cache-dir -r requirements.txt

# 暴露應用程式埠
EXPOSE 5000

# 啟動應用
CMD ["python", "app.py"]
