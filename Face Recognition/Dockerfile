FROM python:3.9-slim

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    build-essential \
    cmake \
    libopenblas-dev \
    liblapack-dev \
    libx11-dev \
    libgtk2.0-dev \
    libboost-python-dev \
    libgl1 \
    pkg-config \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir --default-timeout=100 -r requirements.txt \
    -i https://pypi.org/simple \
    --trusted-host pypi.org \
    --trusted-host files.pythonhosted.org

COPY . .

EXPOSE 5000

CMD ["flask", "run", "--host=0.0.0.0"]