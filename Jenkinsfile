pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    credentialsId: 'github-jenkins',
                    url: 'https://github.com/RE-ZERO-In-And-Out/testRepo.git'
                echo 'hi'
            }
        }
    }
}
