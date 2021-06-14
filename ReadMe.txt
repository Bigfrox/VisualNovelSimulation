시스템 환경변수 Path에 추가
C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Debug
C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Release


cmd 관리자권한
setx Path "%PATH%;C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Release" -m
setx Path "%PATH%;C:\Users\%USERNAME%\Desktop\ship\opencv_3.4.8\bin\Debug" -m

=> 배치파일(env.bat)을 관리자 권한으로 실행하세요.


플레이 exe 파일은 unity_shipduck.exe 파일입니다.