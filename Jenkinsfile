pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'cd /MywebApp && mvn clean package'
            }
        }
    }
}