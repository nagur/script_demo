pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the application..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                Stage("Monitor"){
                    steps {
                        echo "Monitoring my app"
                    }
                }
            }
        }
    }
}
