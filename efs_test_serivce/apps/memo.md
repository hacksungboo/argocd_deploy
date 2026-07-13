
### imgae-backend:1.0, image-frontend:1.0 이미지를 생성해서 Docker hub 에 업로드

```bash

# 이미지 생성하기
docker build -t 계정/이미지명:tag .
docker build -t hsboo/image-backend:1.0 .
docker build -t hsboo/image-frontend:1.0 .
# docker hub 에 push 하기
docker push 계정/이미지명:tag
docker push hsboo/image-backend:1.0
docker push hsboo/image-frontend:1.0


```