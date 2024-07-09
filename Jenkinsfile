pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/yuvalilo/0105.git'
                bat 'python test.py'
            }
        }
    }
}
