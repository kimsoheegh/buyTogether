#base image
FROM node:16.13.0-alpine

# set working directory
#작업을 수행할 디렉토리를 지정
WORKDIR /app

#현재 경로에 있는 것을 app으로 복사
COPY . /app

# 이미지가 빌드 될때 실행
RUN npm install

# 1. frontend 폴더에서 npm install