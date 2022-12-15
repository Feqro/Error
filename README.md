#Error: google api 활용 권한 오류
DefaultCredentialsError google.auth.exceptions.DefaultCredentialsError: Could not automatically determine credentials. Please set GOOGLE_APPLICATION_CREDENTIALS or explicitly create credentials and re-run the application.

#Solution:
환경변수 설정
이름: GOOGLE_APPLICATION_CREDENTIALS
값: 파일의 절대경로\파일명.json
(ex. C:\dev\ws_spring\Projectwo\src\main\resources\wepapp\firebase_service_key.json)


