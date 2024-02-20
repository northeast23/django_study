# django_study
## Django 최초 셋팅
1. 윈도우즈 파일검색기 에서 사용할 폴더에서 VS Code 어드민으로 연다. (main 만들지 않음)
2. 파워쉘 (Ctrl + ` )
3. >> python —version
4. >> mkdir mysite
5. >> cd mysite
6. >> python -m venv venv
7. >> .\venv\Scripts\activate
8. (venv) ..>> pip install django
9. (venv) ..>> django-admin startproject tutorialdjango .  (띄고 쩜이 현재 폴더에 한다)
10. python [manage.py](http://manage.py) migrate
11. python [manage.py](http://manage.py) startapp main   (메인 만들어짐)
12. tutorialdjango.[settings.py](http://settings.py) 수정 
13. utorialdjango.[urls.py](http://urls.py) 수정 
14. [views.py](http://views.py) 수정
15. main폴더에서 template 폴더 와, 그 아래에 다시 main 폴더 만들어서, 웹사이트의 페이지.html 파일들을 넣음 
16. git bash ~ templates/main>>touch index.html about.html notice.html user.html  
17. python [manage.py](http://manage.py) runserver 
    1. 여기서 오류 나는 경우: 파워쉘을 관리자권한으로 연 후 
    2. Set-ExecutionPolicy Unrestricted : a(전부) 실
18. 나중에 가상환경 지우기 (파일 너무 많음)
