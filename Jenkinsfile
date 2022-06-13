pipeline {
    
    agent any
    
    parameters{
        booleanParam(name : 'TEST_ENV', defaultValue: false)
    }
    
    stages{
        stage('Build'){
            steps{
                echo "TEST ENV is ${params.TEST_ENV}"
                echo "Building this"
            }
        }
        
     stage('test'){
            steps{
                echo "Testing this"
            }
        }
        
        stage('Publish'){
            steps{
                echo "Pusbish this"
                echo "Ideally this should be done here"
            }
        }
        
       stage('Notify'){
           steps{
               echo "neeed based notification"
           }
       }

    }
}