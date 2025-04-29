pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo 'Compiling Java program...'
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running Java program...'
                bat 'java HelloWorld'
            }
        }
    }
}
