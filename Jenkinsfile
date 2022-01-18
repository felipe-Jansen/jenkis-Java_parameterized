pipeline {
    agent any

    stages {
        stage('System') {
            steps {
                git 'https://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@github.com/felipe-Jansen/parameterized.git'

                script {
                    def userInput = input(
                                            id: 'userInput', message: 'Informe seu nome',
                                            parameters: [
                                                    string(defaultValue: 'None',
                                                            description: 'Seu nome',
                                                            name: 'nome')
                                            ])
                }

                sh "./gradlew bootRun --args='Felipe'"
            }
        }
    }
}
