# Library Management System

## 目錄

- [簡介](#簡介)
- [安裝](#安裝)
- [使用方法](#使用方法)
- [功能](#功能)
- [貢獻](#貢獻)
- [許可](#許可)

## 簡介

這是一個基於 Django 的線上圖書館管理系統，提供查看圖書館書單、借書、還書、顯示借閱期限和逾期狀態的功能。此外，還包含一個客服對話 Chatbot 功能。

## 安裝

請按照以下步驟安裝和運行此項目：

```bash
# 克隆項目
git clone https://github.com/alexchen9419/library-system.git

# 進入項目目錄
cd 你的項目名

# 建立虛擬環境
python3 -m venv env

# 啟動虛擬環境
source env/bin/activate

# 安裝依賴
pip install -r requirements.txt

# 遷移數據庫
python manage.py migrate

# 啟動伺服器
python manage.py runserver
