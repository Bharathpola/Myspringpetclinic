pipeline {
    agent any
    stages {
        stage('vcs') {
            steps {
                git branch: "main", url: 'https://github.com/Bharathpola/myspringpetclinic.git'
            }
            
        }
        stage('Build the Code') {
            steps {
                sh script: 'mvn clean install'
            }
        }
        
    }

}
