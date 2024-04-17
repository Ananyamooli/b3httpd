pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('prodDeploy') {
            when
            environment name: 'DEPLOY_TO', value: 'other'
        }
        steps {
            echo 'Deploying to production'
        }
    }
}
