pipeline {
    agent any 
    stages{
        stage('BUILD1') {
            steps{
                 sh '''
                    sleep 5
                    echo "This is a BUILD stage"
                '''
            }
        }
        stage('BUILD2') {
            steps{
                 sh '''
                    sleep 5
                    echo "This is a BUILD stage"
                '''
            }
        }


        stage('TEST') {
            steps{
                sh '''
                    sleep 6
                    echo "This is a TEST stage"
                '''
            }
        }   
        stage('Test2') {
            steps{
                 sh '''
                    sleep 5
                    echo "This is a Test2 stage"
                '''
            }
        }

        stage('DEPLOY') {
            steps{
                sh '''
                    sleep 5
                    echo "This is a DEPLOY stage"
                    exit 1
                '''
            }
        }
    }
}

