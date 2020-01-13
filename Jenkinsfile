pipeline{
    agent any
    environment {
        HTTP_PROXY = 'http://proxy.intra.bt.com:8080'
        HTTPS_PROXY    = 'https://proxy.intra.bt.com:8080'
    }
    tools {nodejs "Node-Build"}
    stages {
        stage('Build') {
            steps {
                sh'pwd'
                sh'node --version'
                sh'npm --version'
                sh'npm install'
            }
        }
    }
}    
