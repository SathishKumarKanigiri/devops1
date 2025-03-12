pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Bye') {
            steps {
                echo 'Good Bye'
                echo "test webhook trigger by disabling the pipeline job"
            }
        }
    }
}
