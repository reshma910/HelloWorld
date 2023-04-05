pipeline {

    agent any 

    stages {

        stage(‘Build’) { 

            steps {

                echo 'build step'
            }

        }

        stage(‘Test’) { 

            steps {
              echo 'Test step'
            }

        }

        stage(‘Deploy’) { 

            steps {
              echo 'Deploy Test'
            }

        }
        stage('build image'){
              
            steps{
               sh 'docker build -t reshmapatel1999/my-app:2.0.0 .'
            }
        }

    }

}
