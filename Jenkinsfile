pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from SCM!'
                script {
                    def sum = 15 + 27
                    echo "15 + 27 = ${sum}"
                }
            }
        }
    }
}
