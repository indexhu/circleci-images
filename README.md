
# Docker

### build
```
docker build -t indexhu/circleci .
```

### run
```
docker run indexhu/circleci
```

### tag
```
docker tag <--image-id--> indexhu/circleci:<--tag-->
```

### push
```
docker login
docker push indexhu/circleci:<--tag-->
```
