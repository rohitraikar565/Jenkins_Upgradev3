pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is pooja i love you from LevelUp360'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Productionin') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
