pipeline{
    agent any
    tools {nodejs "Node-Build"}
    stages {
        stage('Build') {
            steps {
                sh'pwd'
                //sh'cd node-js-sample'
                // Run the npm build
                sh'node --version'
                sh'npm --version'
                //sh'export http_proxy=http://proxy.intra.bt.com:8080' 
                //sh'export https_proxy=https://proxy.intra.bt.com:8080'
                sh'npm install'
            }
        }
    }
}    
