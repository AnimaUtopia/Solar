pipeline {
    agent any

    tools {
        nodejs "node-23.9"
    }

    stages {
        stage('VM Node Version') {
            steps {
                sh '''
                    node -v
                    npm -v
                '''
            }
        }
    }
}