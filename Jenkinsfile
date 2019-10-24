pipeline {
    agent any
    stages{
        stage('Stage 1'){
          steps {
            sh 'cat README.md'
            }
            post{
                success{
                    echo "This stage was a success!"
                }
            }
        }
    }
    post {
        always {
            echo "Job complete"
        }
    }
}
