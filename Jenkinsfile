pipeline {
    agent any 
    stages {
        stage('Inicio') {
            echo 'Iniciando ciclo'
        }
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }

    }
}
