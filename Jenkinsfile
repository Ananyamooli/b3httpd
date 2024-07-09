pipeline {
    agent any
    stages {
        stage ('Hotfix Build') {
        steps {
            echo ' Hotfix Build Pipeline'
        }
        }
        stage ('Scan') {
        steps {
            echo 'HotfixScanning Pipelines'
        }
        } 
        stage ('Docker build') {
        steps {
            echo 'Docker Pipelines'
        }
        }
        stage ('Dev Deploy') {
        steps {
            echo 'Dev pipelines'
        }
        }
    }
}
