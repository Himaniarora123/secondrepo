pipeline {
    agent any
    stages {
        stage('stack-creation') {
            steps {
                sh "aws cloudformation create-stack --stack-name myfirststack --template-body file://s3.json --region 'us-east-1'"
            }
        }
    }
}
