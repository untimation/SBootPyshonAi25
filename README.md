# SBootPyshonAi25
스프링 부트와 파이썬을 결합한 AI풀스택 개발

스프링 부트와 파이썬 AI 협업 모듈

개발 환경구축

파이썬 인터프리티 : https://www.python.org/downloads/ -? 3.12버전 설치 (3.8이상 필수)

IDE 설치 : https://www.jetbrains.com/ko-kr/pycharm/download/?section=windows -> 커뮤니티 설치

https://wikidocs.net/book/8531 위키독스
FastAPI 설치 : pip install fastapi uvicorn uvicorn : ASGI(Asynchronus Server Gateway Interface) 는 파이썬에서 비동기 웹서버와 웹 애플리케이션
간의 인터페이스 표준 ASGI는 기존 WSGI(Web Server Gateway Interface)의 비동기 버전으로, 파이썬에서 비동기 처리를 지원하는 웹 애플리케이션을
구축하기 위함 https://velog.io/@hwaya2828/WSGI-ASGI

ASGI 특징

비동기 지원 : ASGI는 비동기 코드실행을 지원하며 높은 성능과 동시성을 제공, 웹소켓이나 서버 푸시와 같은 바동기 통신이 필요한 애플리케이션에
유용한 범용성 : HTTP뿐만 아니라, Websocket, gRPC와 같은 다른 프로토콜로 지원 유연성 : ASGI 애플리케이션은 다양한 서버 및 프레임워크와 호환되며, 모듈식으로 구성 FastAPI와 ASGI

FastAPI는 ASGI 표준을 따르는 웹 프레임워크임 FastAPI 애플리케이션은 비동기 처리를 기본으로 하며, Uvicorn과 같은 ASGI 서버를 사용하여 높은 성능을 제공 FastAPI 서버 실행

main.py 실행 Terminal에서 D:\pythonWorkSpace> uvicorn main:app --reload --port 8001 (위치확인)
