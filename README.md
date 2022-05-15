# 공약한판 - 기호1번 이광재

### 목표
2022년 서울시장선거 기호1번 이광재 후보의 공약을 정리해 보여주는 웹사이트

### 배포 웹사이트
- https://gongyak.kr

### 코드 참고자료
- https://github.com/e-/Josa.js
- https://github.com/iamdustan/smoothscroll

### 이미지 출처
- https://ko.wikipedia.org/wiki/페이스북#/media/파일:Facebook_f_logo_(2019).svg
- https://ko.wikipedia.org/wiki/카카오톡#/media/파일:KakaoTalk_logo.svg
- https://ko.wikipedia.org/wiki/텔레그램#/media/파일:Telegram_2019_Logo.svg

- https://www.flaticon.com/free-icon/upload_130906
- https://www.flaticon.com/free-icon/plus_1828817
- https://www.flaticon.com/free-icon/link_455893


## Building Docker Container
```zsh
$ docker build -t static:latest .
$ docker run -it --rm -p 3000:3000 static:latest
```