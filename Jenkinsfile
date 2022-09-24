pipeline {
    agent any

    stages {
        stage('Develop') {
            steps {
                echo 'Development'
            }
        }
        stage('Build') {
            steps {
                echo 'Building DemoJob'
                build quietPeriod: 5, job: 'DemoJob'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}
