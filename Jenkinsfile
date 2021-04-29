pipeline {
      agent any
      
      stages {
            stage ('compile')
            steps {
                  withMaven(maven : 'Maven') {
                        sh 'mvn clean compile'
                  }
            }
      }
            
