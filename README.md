# company_inner_search_app

社内情報特化型生成AI検索アプリ（Streamlit）

## 概要
- 社内文書検索：入力内容に関連する社内文書を検索
- 社内問い合わせ：社内文書の情報をもとに回答生成

## 起動方法（ローカル）
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements_mac.txt

## 環境変数
プロジェクト直下に `.env` を作成し、以下を設定：```md
## 起動
```bash
streamlit run main.py