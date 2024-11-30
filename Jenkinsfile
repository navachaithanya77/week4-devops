
pipeline {
    agent any
    stages{
        stage('Git access'){
            steps{
                git branch : 'master' ,url :'https://github.com/navachaithanya77/week4-devops.git'
            }
        }

        stage('Java execution'){
            steps{
                bat 'javac hello.java'
                bat 'java hello'
            }
        }
        stage('Python execution'){
            steps{
                bat 'python hello.py'
            }
        }
    }
}
