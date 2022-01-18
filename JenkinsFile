pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://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@github.com/felipe-Jansen/parameterized.git'
                sh './gradlew clean build'
            }
        }
    }
}
