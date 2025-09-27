pipeline {
    agent {
        node {
            label 'maven-build'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/krishnamajja-byte/tweet-trend-new.git'
            }
        }
    }
}
