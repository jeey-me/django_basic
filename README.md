# django_basic
- 디렉토리 생성
```
mkdir django4_ex
cd django4_ex
```
- django 가상환경 만들기, 활성화
```
conda create –n dj4_env python=3.12
conda activate dj4_env
```
- django 라이브러리 설치
```
 pip install django==4.2 
```
- "doit_django" 라는 프로젝트 생성
```
django-admin startproject doit_django .
```
- django 기본 DB 생성
```
python manage.py migrate 
```
- django 서버 실행
```
python manage.py runserver
```
- django 관리자 계정 생성
```
python manage.py createsuperuser
```
- 사용자 페이지 : http://127.0.0.1
- 관리자 페이지 : http://127.0.0.1/admin