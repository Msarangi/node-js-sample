pipeline{
    agent any
    tools {nodejs "Node-Build"}
    stages {
        withEnv(['HTTP_PROXY=http://proxy.intra.bt.com:8080'],['HTTPS_PROXY=https://proxy.intra.bt.com:8080']) {
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
}    
