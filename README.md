# company_inner_search_app

社内情報特化型生成AI検索アプリ（Streamlit）

---

## 概要

本アプリは、社内文書をもとに  
**情報検索および問い合わせ対応を行う生成AIアプリ**です。

---

## 機能

### 社内文書検索
入力内容に関連する社内文書を検索します。

### 社内問い合わせ対応
社内文書の情報をもとに、自然言語で回答を生成します。

---

## 起動方法（ローカル / Mac）

### 1. 仮想環境の作成・有効化

```bash
python3 -m venv env
source env/bin/activate

---

### 2. パッケージのインストール

仮想環境を有効化した状態で、  
アプリの動作に必要なパッケージをインストールします。

```bash
pip install -r requirements_mac.txt
※ Windows の場合は requirements_windows.txt を使用してください。

### 3. 環境変数の設定（重要）

OpenAI API を使用するため、  
プロジェクト直下に **`.env` ファイル** を作成し、  
以下の内容を記載してください。

```env
OPENAI_API_KEY=YOUR_API_KEY
注意
	•	.env（APIキーを含むファイル）は GitHub にコミットしません
	•	env/（仮想環境フォルダ）も Git 管理しません
	•	これらは .gitignore により除外されています

### 4. アプリの起動

以下のコマンドを実行し、  
Streamlit アプリを起動します。

```bash
streamlit run main.py
起動後、ブラウザで以下にアクセスしてください。
http://localhost:8501