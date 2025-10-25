pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git(
                    url: 'https://github.com/Shaikraz1997/ccna.git',
                    branch: 'master',
                    credentialsId: '614c678b-d999-4ace-a8a8-1955f4554905'
                )
            }
        }
    }
}
