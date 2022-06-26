pipeline {
    agent any

    stages {
        stage('Build') {
            when{
                    buildingTag()
                }
            steps {
                echo 'Hello World Tag'
            }
        }
    }
}
