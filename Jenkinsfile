pipeline {
    agent any

    stages {
        stage('System') {
            steps {
                script {
                    sh "./gradlew bootRun --args='${default_nome}'"
                }

            }
        }
    }
}
