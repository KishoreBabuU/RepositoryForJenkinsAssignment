pipeline {
    agent any
    
    stages {
        stage('Hello World') {
            steps {
                script {
                    checkout scm
                    bat 'javac HelloWorld.java && java HelloWorld'
                }
            }
        }
        
        stage('Hello Wipro') {
            steps {
                script {
                    checkout scm
                    bat 'javac HelloWipro.java && java HelloWipro'
                }
            }
        }

        stage('Hello Jenkins') {
            steps {
                script {
                    checkout scm
                    bat 'javac HelloJenkins.java && java HelloJenkins'
                }
            }
        }
    }
    
    post {
        always {
            echo 'Pipeline completed'
        }
    }
}
