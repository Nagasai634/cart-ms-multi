pipeline {
    agent any
    stages {
        stage('building the code') {
            steps {
                echo "built the code"
            }
        }
    }
    post {
            success {
                echo "if pipeline is success"
            }
            failure {
                echo "if pipeline is failure"
            }
            always {
                echo "if pipeline is failure or sucsess doesn't matter print it"
            }
    }
}
