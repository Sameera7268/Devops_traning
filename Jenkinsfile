pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('GIT CLONE') {
            steps {
                git branch: 'main', url: 'https://github.com/ravdy/tweet-trend-new.git'
            }
        }
    }
}