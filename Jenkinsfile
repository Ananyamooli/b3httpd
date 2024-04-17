pipeline{
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('prod Deploy') {
            when {
                equals expected: 5, actual: currentBuildnumber
            }
            steps {
                echo 'deploying to production'
            }
        }
    }
}
