From python:3

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
WORKDIR /usr/src/app


CMD ["python", "runtime.py"]
