pipeline {
    agent {
        node {
            label 'maven-build'
        }
    }
    environment {
        PATH = "/opt/apache-maven-3.9.11/bin:/usr/lib/jvm/java-17-openjdk-amd64/bin:$PATH"
    }

    stages {
        stage("build") {
            steps {
                sh 'mvn clean deploy'
            }
        }
    
    }
}
