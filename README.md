# docker-example
생활코딩 Docker 입구 수업을 듣고 정리한 내용입니다.

### 1. 설치
docker desktop 설치

### 2. 이미지
- 이미지 다운로드
```
docker pull [이미지명]
```
- 이미지 삭제
```
docker rmi [이미지명] 
```
### 3. 컨테이너
![](https://user-images.githubusercontent.com/61075048/151774366-b2ece034-3ec3-44d6-8f5c-35e8beac2d4e.png)
- 컨테이너 실행
```
docker exec -it [컨테이너명] /bin/sh
```
### 4. 네트워크
![](https://images.velog.io/images/eunz_juu/post/b9d51bf4-6063-4678-a9a5-ed39bf3206a6/image%20(1).png)
- 포트포워딩 
```
docker run --name [지정한 이미지파일명] -p [호스트 port]:[Container 포트] [이미지파일명]
```
