pipeline {
    agent any
    stages {
        stage('1. Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('2. Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests...'
               
            }
        }

        stage('3. Code Analysis') {
            steps {
                echo 'Running ESLint code analysis...'
             
            }
        }

        stage('4. Security Scan') {
            steps {
                echo 'Running npm audit...'
               
            }
        }

        stage('5. Deploy to Staging') {
            steps {
                echo 'Deploying to staging server...'
               
            }
        }

        stage('6. Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging...'
               
                
            }
        }

        stage('7. Deploy to Production') {
            steps {
                echo 'Deploying to production server...'
               
            }
        }
    }
}
