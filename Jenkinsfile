pipeline{
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('prodDeploy') {
            when {
                equals expected: 5, actual: currentBuild.number
            }
            steps {
                echo 'deploying to production'
            }
        }
    }
}
