pipeline {
    agent {
        node {
            label'maven'
        }
    }

    stages {
        stage('clone the code from github') {
            steps {
                git branch: 'main', url: 'https://github.com/ravdy/tweet-trend.git'
            }
        }
    }
}

