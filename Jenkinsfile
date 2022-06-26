pipeline {
    agent any

    stages {
        stage('Build') {
            when{
#                    buildingTag()
#		     tag "4.0"
		     changelog '_*some_test.*'
                }
            steps {
                echo 'Hello World Tag'
            }
        }
    }
}
