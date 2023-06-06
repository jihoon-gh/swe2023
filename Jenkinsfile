pipeline {
    agent {
        label 'swe2023'
    }
    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                    credentialsId: 'github_access_token',
                    url: 'https://github.com/jihoon-gh/swe2023.git'
            }
        }
    }
}