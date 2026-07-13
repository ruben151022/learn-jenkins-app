pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'touch test.txt'
                sh 'echo "this is a tst file" >> test.txt'
            }
        }
    }
}
