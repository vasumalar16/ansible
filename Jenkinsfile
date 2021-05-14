pipeline {
    agent {
        label 'demo_slave'
    }

    stages {
        stage('git') {
            steps {
                git branch: 'main', changelog: false, credentialsId: 'git_credentials', poll: false, url: 'https://github.com/vasumalar16/ansible'
            }
        }
    }
}

