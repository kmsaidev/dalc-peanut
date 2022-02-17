# dalc-peanut

* git clone https://github.com/EUNDINI/dalc-peanut

* git clone 한 뒤에 순서대로 입력하기

* git init


```터미널 git bash로 실행하기``` 

# 가상환경 

* python -m venv myvenv      
* source myvenv/Scripts/activate

* pip install django  
* pip install pillow 

* 폴더 안으로 이동 : cd dalc-peanut

# 클론 끝나고 필요시 사용할 명령어랑 깔아야 할 것 목록
 이거 하려면 secrets.json 파일추가하고 은영 시크릿키 넣어야함 필요하신분 은영이에게 연락쥬세요ㅕ >,< (secrets.json 위치 = manage.py랑 같은 위치)

* python manage.py collectstatic (static파일 모으는 거)

* python manage.py makemigrations

* python manage.py migrate

* python manage.py runserver

# AI 관련 install 목록
* pip install numpy
* pip install sklearn
* pip install joblib

# 계정
* (admin superuser 이 계정으로 로그인해도 되고 새로만들어도 됨 
* -중간에 데이터날리면서 사라질경우 python manage.py createsuperuser 해서 생성해주기

* id :dalc  #pw :aa112233    )
