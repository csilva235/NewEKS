## To Build
```
$(aws ecr get-login --no-include-email --region us-west-2)
docker build -t 750796802028.dkr.ecr.us-west-2.amazonaws.com/acg.eks.bookstore.front-end:latest .
docker push 750796802028.dkr.ecr.us-west-2.amazonaws.com/acg.eks.bookstore.front-end:latest
```