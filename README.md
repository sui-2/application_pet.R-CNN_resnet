
# application_pet.R-CNN_resnet
---
<img width="1122" height="504" alt="スクリーンショット (16)" src="https://github.com/user-attachments/assets/8c05fda1-1d2e-400c-a8e3-a55152a5a24b" />

---
# Overview
This application allows users to process animal face images by selecting and applying various items. 
The app works by integrating a Python-based ML model with a FastAPI backend.

As a member of a 4-person machine learning team responsible for face and landmark detection, I focused on the landmark detection model, which identifies 9 key points on a pet's face.

---
## How to Start the System

This is a web application built with **FastAPI** and **Docker**.

## Prerequisites
*   **Docker Desktop** must be installed.

## Setup Instructions
1.  Download the `pet_app` directory and navigate into it:
    ```bash
    cd pet_app
    ```
2.  Build the Docker image (this may take some time):
    ```bash
    docker build -t pet_app .
    ```
3.  Run the Docker container:
    ```bash
    docker run -p 8000:8000 pet_app
    ```
4.  Open your browser and access the following URL:
    [http://127.0.0.1:8000/static/pet.html](http://127.0.0.1:8000/static/pet.html)

### Note
*   Steps 2 and 3 may take some time depending on your environment.
---

【システム起動方法】

これは、FastAPIとDockerで構築されたWebアプリケーションです。

前提条件:
Docker Desktopがインストールされている

1. pet_app ディレクトリをダウンロードし、pet_app内へ移動する。
2. Docker 実行環境が整っている環境で docker build -t pet_app . を実行する。
3. docker run -p 8000:8000 pet_app を実行する。
4. ブラウザで以下のURLにアクセスしてください。: http://127.0.0.1:8000/static/pet.html

※注意事項
・手順2、3は時間がかかる場合があります。
