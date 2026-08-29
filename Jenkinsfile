pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                script{
                    sh """ 
                        echo "Building"
                    """
                }
            }
        }
        stage {
            steps {
                script{
                    sh """
                        echo "Testing" 
                    """
                }
            }
        }
        stage {
            steps {
                script{
                    sh """
                        echo "Deploying"
                    """
                }
            }
        }
    }
    
}