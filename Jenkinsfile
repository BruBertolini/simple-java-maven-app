pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withMaven( maven : 'Maven 3.3.3') {
                    bat 'mvn -B -DskipTests clean package'
                }
            }
        }
    }
}
