pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

                    sh 'mvn clean compile'
           
        }

        stage ('Testing Stage') {

       
                    sh 'mvn test'
               
        }


        stage ('Deployment Stage') {
           
                    sh 'mvn deploy'
           
        }
    }
}
