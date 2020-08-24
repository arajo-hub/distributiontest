# distributiontest

헤로쿠 배포에 계속 실패하다가 성공한 방법

1. heroku buildpacks:set heroku/python 입력

2. heroku config:set DISABLE_COLLECTSTATIC=1 입력

3. git push heroku master 입력

* settings.py파일의 allowed_hosts에 '.herokuapp.com' 추가해주는 거 잊지 말기
