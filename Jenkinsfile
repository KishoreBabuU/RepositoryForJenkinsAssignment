pipeline {
    agent any
    
    stages {
        stage('Hello World') {
            steps {
                script {
                    checkout scm
                    bat 'javac C:\\Users\\dell\\eclipse-workspace\\JenkinsAssignment\\src\\HelloWorld.java'
                }
            }
        }
        
        stage('Hello Wipro') {
            steps {
                script {
                    checkout scm
                    bat 'javac C:\\Users\\dell\\eclipse-workspace\\JenkinsAssignment\\src\\HelloWipro.java'
                }
            }
        }

        stage('Hello Jenkins') {
            steps {
                script {
                    checkout scm
                    bat 'javac C:\\Users\\dell\\eclipse-workspace\\JenkinsAssignment\\src\\HelloJenkins.java'
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
