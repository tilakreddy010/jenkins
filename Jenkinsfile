pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            // sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://simplests3cft.json --region 'us-east-1'"
            sh "aws cloudformation create-stack --stack-name efs-jenkins --template-body file://efs.yaml --region 'us-east-1'"
              }
             }
            }
            }
