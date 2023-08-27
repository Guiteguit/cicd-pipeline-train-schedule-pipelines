pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the App'
                ./gradlew build --no-daemon
            }
        }
    }
}
