pipeline {
  agent any
  stages {
    stage('Deploy to s3') {
      steps{
              sh 'aws s3 cp index.html s3://myjenkinsstaticweb'
           }
        }
    }
}
