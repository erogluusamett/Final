pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Örneğin, bisrddddd Maven projesi inşa etmek için
                // sh 'mvn cdsstddddddddlean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Örneğin, testleri çalıştırmak için
                // sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Örneğin, bir sunucuya dağıtmak için
                // sh 'scp target/gbmyabhvpp.jar user@server:/path/to/deploy/'
            }
        }
    }

    post {
        always {
            echo 'This will alwassys run'
        }
        success {
            echo 'This wilsl run only if successful'
        }
        failure {
            echo 'This will run only if failed'
        }
    }
}