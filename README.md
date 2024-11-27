docker build -t my-app:v1.0 .

docker tag my-app:v1.0 582175642363.dkr.ecr.eu-north-1.amazonaws.com/ecr-jenkins-pipeline:v1.0

docker push 582175642363.dkr.ecr.eu-north-1.amazonaws.com/ecr-jenkins-pipeline:v1.0

docker build -t my-app:v2.0 .

docker tag my-app:v2.0 582175642363.dkr.ecr.eu-north-1.amazonaws.com/ecr-jenkins-pipeline:v2.0

docker push 582175642363.dkr.ecr.eu-north-1.amazonaws.com/ecr-jenkins-pipeline:v2.0
