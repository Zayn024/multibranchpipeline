pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is sprint1 latest branch..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
