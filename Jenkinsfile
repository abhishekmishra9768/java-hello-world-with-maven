pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/your-repo/your-project.git', branch: 'master'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn clean install'
            }
        }
    }
}
