pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/edgar-tc/Jenkins-Trigger-.git']])
            }
        }
    }
}
