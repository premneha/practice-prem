pipeline {
    agent {
        label 'slave 1'
    }

    stages {
        stage('Build Master') {
            options {
                timestamps()
            }
            when {
                branch 'main'
            }
            steps {
                echo 'Hello World main'
            }
            
        }
        
        stage('Build dev') {
            options {
                timestamps()
            }
            when {
                branch 'dev'
            }
            steps{
                echo 'Hello Wordls dev'
            }
        }
    }
}
