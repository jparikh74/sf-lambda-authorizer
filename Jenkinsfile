pipeline {
    agent any
    stages {
        stage('List production S3 buckets') {
            steps {
                withMaven {
                    sh "mvn install -Dmaven.test.skip=true"
                }
            }
        }
    }
}
