# az-2007-20260227-2

FastAPI を使用した Hello World API のサンプルプロジェクトです。

## 構成

```
.
├── src/
│   └── main.py          # FastAPI アプリケーション
├── tests/
│   └── test_main.py     # pytest 単体テスト
├── requirements.txt     # 依存ライブラリ
└── README.md
```

## セットアップ

```bash
pip install -r requirements.txt
```

## サーバー起動

```bash
uvicorn src.main:app --reload
```

サーバー起動後、http://localhost:8000/ にアクセスすると `{"message": "Hello World"}` が返されます。

## テスト実行

```bash
pytest tests/
```