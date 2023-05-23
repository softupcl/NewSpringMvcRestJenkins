pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'github_access_ssh', url: 'https://github.com/softupcl/NewSpringMvcRestJenkins.git'
            }
        }
    }
}