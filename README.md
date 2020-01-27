
# Docker

### build
docker build -t indexhu/circleci .

### run
docker run indexhu/circleci

### tag
docker tag <image-id> indexhu/circleci:v741

### push
docker login
docker push indexhu/circleci:v741
