pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/rotemss/repo-testing.git'
                bat dir
            }
        }
    }
}
