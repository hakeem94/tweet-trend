pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/hakeem94/tweet-trend.git'
            }
        }
    }
}
