pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('prodDeploy') {
            when {
            environment name: 'DEPLOY_TO', value: 'production'
        }
        steps {
            echo 'Deploying to production'
        }
    }
}
}  
