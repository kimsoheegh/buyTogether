#java 11 사용
FROM openjdk:11-jdk

#기본 작업 디렉토리 설정
WORKDIR /app

#jar파일 생성 후 복사
ADD build/libs/project-0.0.1-SNAPSHOT.jar /app/app.jar

#컨테이너가 실행될 때 명령어 수행
ENTRYPOINT ["java","-jar","/app/app.jar"]

# 1. backend 폴더에서 ./gradlew build 실행
# 2. build/libs에 backend-0.0.1-SNAPSHOT.jar 생성 확인Í