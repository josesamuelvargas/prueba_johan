pipeline {
    agent none {
        docker { image 'maven:3.8.1-adoptopenjdk-11' }
    }
    stages {
        stage('Compilacion') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
