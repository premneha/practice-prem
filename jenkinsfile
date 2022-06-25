pipeline {
    agent any

    stages {
        stage('Build Master') {
            when {
                branch 'main'
            }
            steps {
                echo 'Hello World main'
            }
            
        }
        
        stage('Build dev') {
            when {
                branch 'dev'
            }
            steps{
                echo 'Hello Wordls dev'
            }
        }
    }
}
