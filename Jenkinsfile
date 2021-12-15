pipeline {
    agent { 
        docker { 
            image 'php:7.4-fpm' 
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'ls -al'
            }
        }
    }
}