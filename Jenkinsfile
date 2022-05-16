pipeline {
    agent any

    stages {
        stage('Passo 1') {
            steps {
                script {
                    sh "./gradlew bootRun --args='${default_nome}'"
                }

            }
        }
    }
}
