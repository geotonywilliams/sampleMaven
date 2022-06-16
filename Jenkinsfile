pipeline{
agent any

stages {
  stage('maven install') {
    steps {
        withMaven(jdk: 'JDK9', maven: 'Maven3') {
                   sh 'mvn clean install'
                }
            }
        }

    }

}
