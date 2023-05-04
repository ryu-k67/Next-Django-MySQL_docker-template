# Next-Django-MySQL_docker-template

- フロントエンド：Next.js
- バックエンド&emsp;：Django
- データベース&emsp;：MySQL
- インフラ&emsp;&emsp;&emsp;：Docker
  
上記を設定したdockerのテンプレート

## コマンド
docker-compose build  
- コンテナ作成・起動  
docker-compose up -d  
- コンテナ停止・削除  
docker-compose down  
- コンテナ起動のみ  
docker-compose start  
- コンテナ停止のみ  
docker-compose stop  
- コンテナの状態確認  
docker-compose ps  
<br>

- backend(Django)環境のコンテナへ入る  
docker-compose exec django /bin/bash  
- backend(Django)立ち上げ  
python manage.py runserver 0.0.0.0:8000  
<br>

- frontend(Next.js)環境のコンテナへ入る  
docker-compose exec next /bin/bash  
- frontend(Next.js)立ち上げ  
cd app  
npm run dev
