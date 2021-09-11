# Flask 기반 Python Back-end Framework
2021 PMDS+

# 1. Flask 실행하기
## MacOSX
export FLASK_APP=pybo/__init__.py <br/>
export FLASK_ENV=development

## Windows
set FLASK_APP=pybo/__init__.py<br/>
set FLASK_ENV=development

## 위 명령어 실행 후
flask run


# 2. Docker 활용하기
--> 사전에 docker-compose에 MariaDB 정보 추가하였음. Docker만 설치되어있다면, 별도로 DB를 설치할 필요없다.
docker-compose.yml 파일 추가<br/>
docker compose up -d<br/>
docker exec -it {name} bash<br/>
mysql -uroot -p


# 3. git w/t CUI
git pull<br/>
git add .<br/>
git commit -m "ddl added"<br/>
git push origin main



# 0. 기타
## DB 변경
SQLite -> MariaDB<br/>
참고자료 : https://pythonq.com/so/python/102893


# 9. Notion 정보
https://thj0309.notion.site/Python-s-backend-Flask-d386bd4a932c4bfda69d94712093090a
