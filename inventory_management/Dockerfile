# 使用官方 Python 镜像
FROM python:3.9-slim

# 设置工作目录
WORKDIR /app

# 复制应用文件
COPY . /app

# 安装依赖项
RUN pip install --no-cache-dir -r requirements.txt

# 暴露应用运行的端口
EXPOSE 5000

# 启动应用
CMD ["python", "app.py"]
