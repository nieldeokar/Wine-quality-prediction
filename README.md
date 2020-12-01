# Wine Quality Prediction | Assignment 2

Goal: The purpose of this individual assignment is to learn how to develop parallel machine learning (ML) applications in Amazon AWS cloud platform. Specifically, you will learn: (1) how to use Apache Spark to train an ML model in parallel on multiple EC2 instances; (2) how to use Spark’s MLlib to develop and use an ML model in the cloud; (3) How to use Docker to create a container for your ML model to simplify model deployment.

## Full Readme 
* [Readme word]()

## Docker image link
* [Docker image : nieldeokar/wine-prediction-mvn:1.0](https://hub.docker.com/layers/nieldeokar/wine-prediction-mvn/1.0/images/sha256:8f426593aa0cbd302b5705561091f5f3e67f564b60d07955508686a9d24fcb51)

Docker run instructions
docker pull nieldeokar/wine-prediction-mvn:1.0

Docker run -v [fullLocalPath of TestDataset.csv: data/TestDataset.cvs ] nieldeokar/wine-prediction-mvn:1.0

for e.g.

docker run -v /Users/niel/Desktop/docker-attempt/TestDataset.csv:/data/TestDataset.csv nieldeokar/wine-prediction-mvn:1.0
 


