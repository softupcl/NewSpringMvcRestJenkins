pipeline {
    agent any 
    tools { 
        maven 'Maven 3.9.2' 
        jdk 'jdk17' 
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }
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
