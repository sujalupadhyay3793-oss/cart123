pipeline {
    agent { 
        label 'node'
    }
    tools {
        nodejs 'npm'
    }
    environment {
        Name = "Mantasha"
    }

    stages {
        stage('clone') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: 'https://github.com/sujalupadhyay3793-oss/cart123.git'
            }
        }
         stage('build') {
            steps {
                echo 'Hello World'
                sh 'npm i'
            }
        }
         stage('deplyo') {
            steps {
                echo 'Hello World'
                sh 'npm run build'
            }
        }
    }
}
