pipeline {
    agent any

    stages {
        stage('Build') {
            when{
		     changerequest()
                }
            steps {
                echo 'Hello World Tag'
            }
        }
    }
}
