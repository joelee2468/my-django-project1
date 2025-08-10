pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/joelee2468/my-django-project1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Insert your build commands here
                // For COBOL, call mainframe build jobs or compile scripts
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Insert test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Insert deploy commands here (e.g., triggering z/OS jobs)
            }
        }
    }
}
