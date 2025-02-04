=========================================
requirements.txt 파일 사용법
[링크 테스트](https://colab.research.google.com/drive/17shDwyoPjRdKgjEHo8rU217a0XsDG1lf)
------------------------------------------
[주의 사항]
- 쓸데 없는 패키지가 requirements.txt에 목록화 되지 않도록 해주세요.
- requirements.txt는 항상 복원을 먼저 실행한 후, 생성을 실행 해주세요. 안그러면 목록 날아갈 수 있습니다.

1. 복원
PyCharm "Terminal"을 열고 다음의 명령을 실행함으로써 "requirements.txt"에 있는 패키지들을 설치할 수 있다.
------------------------------------------
$ pip install -r requirements.txt
------------------------------------------

2. 생성
requirements.txt는 현재 파이썬 인터프리터 환경에 설치되어 있는 패키지 목록을 담고 있는 텍스트 파일이다.
PyCharm "Terminal"을 열고 다음의 명령을 실행함으로써 손쉽게 "requirements.txt" 파일을 생성할 수 있다.

------------------------------------------
$ pip freeze > requirements.txt
------------------------------------------
