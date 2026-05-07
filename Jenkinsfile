pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
               script{
                    sh """
                        echo "building"
                    """
               }
            }
        }

        stage('test'){
            steps{
                script{
                    sh """
                        echo "Test"
                    """
                }
            }
        }

        stage('Deploy') {
            steps{
                script{
                    sh """
                        echo "Deploy
                    """         
                }
            }
        }
    }
}