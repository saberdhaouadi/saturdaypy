pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 test1'
            }
        }
        stage('test') {
            steps {
                sh 'python3 unittest'
            }
        }
        stage('deploy') {
            steps {
                sh 'python3 deployunit'
            }
        }

      }

    
}
