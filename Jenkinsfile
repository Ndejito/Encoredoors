pipeline {
    agent any
   
    stages {
        stage ('Build') {
            steps {
                sh 'cd /MywebApp && mvn clean package'
            }
        }
    }
}