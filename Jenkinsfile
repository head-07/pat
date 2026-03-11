pipeline {
    agent any
    stages {
        stage('Clone Public Repo') {
            steps {
                git branch: 'main', url: 'https://github.com'
            }
        }
    }
}

