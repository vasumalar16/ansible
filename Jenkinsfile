pipeline {
    agent {
        label 'master'
    }

    stages {
        stage('git') {
            steps {
               git branch: 'dev', changelog: false, credentialsId: 'git_credentials', poll: false, url: 'https://github.com/vasumalar16/ansible' 
            }
        }
    }
}

