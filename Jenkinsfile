pipeline{
agent any

stages {
  stage('maven install') {
    steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'JDK9', maven: 'Maven3', mavenSettingsConfig: 'null') {
                   sh 'mvn clean install'
                }
            }
        }

    }

}
