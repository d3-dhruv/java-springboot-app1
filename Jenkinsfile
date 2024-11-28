pipeline {
    agent any
    tools {
        maven 'maven3'
    }
    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main' , credentialsId: 'git-cred' , url: 'https://github.com/d3-dhruv/java-springboot-app1'

            }
        }

        
    }
}