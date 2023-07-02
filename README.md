# rinna-llm-test
[riina3.6b](人間によるフィードバック学習済み言語モデル)を動かすテスト
* Docker上での動作環境
* GPU対応

# 使い方
1. `docker-compose up -d`でコンテナを起動
2. `docker exec -it rinna-llm-test bash`でコンテナに入る
3. `python3 opt/main.py`で実行