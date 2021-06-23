시스템 환경변수 Path에 추가
C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Debug
C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Release


cmd 관리자권한
setx Path "%PATH%;C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Release" -m
setx Path "%PATH%;C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Debug" -m

=> 배치파일(env.bat)을 관리자 권한으로 실행하세요.


플레이 exe 파일은 unity_shipduck.exe 파일입니다.
아이템창 i
장비창 e
아이템 착용 Z
아이템 탭 이동 X(취소키)
웹캠 가위바위보 인식 후 엔터눌러야함.