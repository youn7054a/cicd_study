# cicd_study

# git action -> ecs fargate
# 서비스에 새로운 태스크 생성

# docker run -p 80:80 --platform linux/amd64 172427596870.dkr.ecr.ap-northeast-2.amazonaws.com/study2

# docker run --platform linux/amd64 172427596870.dkr.ecr.ap-northeast-2.amazonaws.com/study2

# docker exec -w /code/app 75af96bd003c python3 test.py

# docker run -it python 종료되지 않게

# docker run -it memory --100m e05fec54b1d2  --error

# docker update --memory 500m --memory-swap 500m 5f2ced56ba46

# docker exec 5f2ced56ba46 python3 -c 'print(1)'

test111
<!-- docker run -d \
  -it \
  --name devtest4 \
  -v "$(pwd)"/app:/code/app \
  d1c8f5f72a2b -->
