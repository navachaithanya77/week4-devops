pipeline{
    agent any
    stages{
        stage('Git access'){
            steps{
            git branch : 'main',url:""
        }
    }
    stage('Java execution'){
        steps{
            bat 'javac hello.java'
            bat 'hello java'
        }
    }
    stage('Puthon execution'){
        steps{
            bat 'Python hello.py'
           
        }
    }
}
}
