pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git(
                    url: 'https://github.com/Shaikraz1997/myproject1.git',
                    branch: 'master',
                    credentialsId: '9b9993c5-0a92-4279-a6a2-a85efb9dcb7d'
                )
            }
        }
    }
}
