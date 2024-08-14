pipeline {
    agent any

    tools{
            maven 'maven'
    }

    stages {
        stage('Maven Clean'){
            steps{
                sh 'mvn clean'
            }
        }

        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
