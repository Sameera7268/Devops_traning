pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('GIT CLONE') {
            steps {
                git branch: 'main', url: 'https://github.com/Sameera7268/Devops_traning.git'
            }
        }
    }
}