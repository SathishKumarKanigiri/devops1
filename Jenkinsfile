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
        stage('parellel') {
            parallel {
                stage('one') {
                    steps {
                        echo "This is first parallel stage"
                    }
                }
                stage('two') {
                    steps {
                        echo "This is second parallel stage"
                    }
                }
            }
        }
    }
}
