pipeline {
    agent any 
    environment {
        course = 'docker and gcp'
        name = 'sai'
    } 
    stages {
        stage ('classtoday') {
            steps {
                echo "welcome to class $name"
                echo "you enrolled into $course"
            }
        }
        stage('build') {
            steps{
                echo "welcome to my first pipeline"
            }
        }
        stage('sonar') {
            steps {
                echo "scanning the code"
            }
        }
        stage('docker') {
            steps {
                echo "building the docker image"
            }
        }
        stage('kube') {
            steps {
                echo "deploying the k8s"
            }
        }
    }

    }
