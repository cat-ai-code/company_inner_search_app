# company_inner_search_app

社内情報特化型生成AI検索アプリ（Streamlit）

## 概要
- **社内文書検索**：入力内容に関連する社内文書を検索
- **社内問い合わせ**：社内文書の情報をもとに回答を生成

## 起動方法（ローカル / Mac）
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements_mac.txt

プロジェクト直下に .env を作成し、以下を設定：OPENAI_API_KEY=YOUR_API_KEY

起動：streamlit run main.py

補足：
•Windowsの場合は requirements_windows.txt を使用してください。
.env（APIキー）と env/（仮想環境）はGit管理しません。
```