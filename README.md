# application_pet.R-CNN_resnet
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
