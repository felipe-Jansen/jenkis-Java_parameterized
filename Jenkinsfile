pipeline {
    agent any

    stages {
        stage('System') {
            steps {
                git 'https://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@github.com/felipe-Jansen/parameterized.git'

                script {
                    sh "./gradlew bootRun --args='${default_nome}'"
                }


            }
        }
    }
}
