pipeline {
    agent any 
    stages {
        stage('Inicio') {
            steps{
                echo 'Iniciando ciclo'
            }
            
        }
        stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }

    }
}
