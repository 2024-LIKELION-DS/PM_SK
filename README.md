# [과제 예시] 2024 멋쟁이사자처럼 12th : 6차 세션 Read.md 문서 작성법 배우기

## 서비스 소개

#### 반갑습니다

#### 멋쟁이사자처럼 12기 아기사자 진, 승주, 은지, 경민과 함께하고 있는 파트장 이성경입니다.

#### 여러분의 실력을 마음껏 펼쳐보세요

<img src="./pm_12th.jpg" width="500px">

<br>

## 실행 방법
```
#가상환경 설치
python -m venv venv (Window)
virtualenv -p python3 venv (Mac)

#가상환경으로 들어가기
.\venv\Scripts\activate (Window)
source venv/bin/activate (Mac)

#장고설치
pip install django~=3.2.10 

#마이그레이션
python manage.py makemigrations
python manage.py migrate

#가상환경 실행
python manage.py runserver

#가상환경 종료
ctrl + c
```

<br>

## 팀원 소개

<table border="" cellspacing="0" cellpadding="0" width="100%">
  <tr width="100%">
    <td align="center">성경</a></td>
    <td align="center">진</a></td>
    <td align="center">은지</a></td>
    <td align="center">경민</a></td>
    <td align="center">승주</a></td>
  </tr>
  <tr width="100%">
  <td align="center"><img src="pm_12th.jpg" alt="image" border="0" width="90px"></td>
  <td  align="center"><img src="pm_12th.jpg" alt="image" border="0" width="90px"></td>
  <td  align="center"><img src="pm_12th.jpg" alt="image" border="0" width="90px"></td>
    <td  align="center"><img src="pm_12th.jpg" alt="image" border="0" width="90px"></td>
  <td  align="center"><img src="pm_12th.jpg" alt="image" border="0" width="90px"></td>
  </tr>
  <tr width="100%">
  <td  align="center">기획/디자인</td>
    <td  align="center">기획/디자인</td>
  <td  align="center">기획/디자인</td>
  <td  align="center">기획/디자인</td>
    <td  align="center">기획/디자인</td>
     </tr>
      <tr width="100%">
     </tr>
  </table>

<br>

## 기술 스택

<span>Front End :</span> 
<span><img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"></span>

<span>Back End: </span>
<span><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white"></span>

<span>Environment: </span>
<span><img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/pycharm-000000?style=for-the-badge&logo=pycharm&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"></span>

<span>Communication: </span>
<span><img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"></span>

<span>Design: </span>
<span><img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"></span>

<br>

## 화면 구성

<img src="./pm_12th.jpg">

<br>

## API 명세서

<img width="1203" alt="pm_12th_likelion" src="./pm_12th.jpg">
<br>

## 폴더 구조

  ```
📂 all_project
└─yuyong
├─ yuyong
│  ├─ **init**.py
│  ├─ [asgi.py](http://asgi.py/)
│  ├─ [settings.py](http://settings.py/)
│  ├─ [urls.py](http://urls.py/)
│  └─ [wsgi.py](http://wsgi.py/)
├─ post
│  ├─ **init**.py
│  ├─ [admin.py](http://admin.py/)
│  ├─ [apps.py](http://apps.py/)
│  ├─ [models.py](http://models.py/)
│  ├─ [tests.py](http://tests.py/)
│  ├─ urls.py

│  ├─ forms.py

│  └─ [views.py](http://views.py/)

├─ qna
│  ├─ **init**.py
│  ├─ [admin.py](http://admin.py/)
│  ├─ [apps.py](http://apps.py/)
│  ├─ [models.py](http://models.py/)
│  ├─ [tests.py](http://tests.py/)
│  ├─ urls.py

│  ├─ forms.py

│  └─ [views.py](http://views.py/)

├─ user
│  ├─ **init**.py
│  ├─ [admin.py](http://admin.py/)
│  ├─ [apps.py](http://apps.py/)
│  ├─ [models.py](http://models.py/)
│  ├─ [tests.py](http://tests.py/)
│  ├─ urls.py

│  ├─ forms.py

│  └─ [views.py](http://views.py/)
└─ [manage.py](http://manage.py/)
  ```

