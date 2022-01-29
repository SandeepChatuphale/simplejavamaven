pipeline {
    agent any

    stages 
    {
        stage('clean') 
        {
            steps 
            {
                bat 'mvn -X clean'
            }
        }
        stage('compile') 
        {
            steps 
            {
                bat 'mvn -X compile'
            }
        }
        
        stage('package') 
        {
            steps 
            {
                bat 'mvn -X package'
            }
        }


    }
}
