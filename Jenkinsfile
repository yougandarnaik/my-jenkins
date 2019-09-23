pipeline {
    agent { docker { image 'node:6' } }
    stages {
        stage1('RUN') {
            steps {
                sh 'npm cache clean'
            }
        },
            stage2('build') {
            steps {
                sh 'npm install'
                sh 'npm --version'
            }
        },
        stage3('EXPOSE') {
            steps {
                sh '4200'
            }
        }
    }
}
