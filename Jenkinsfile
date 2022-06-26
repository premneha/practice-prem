pipeline {
    agent any

    stages {
        stage('Build') {
            when{
		     changelog '_*some_text.*'
                }
            steps {
                echo 'Hello World Tag'
            }
        }
    }
}
