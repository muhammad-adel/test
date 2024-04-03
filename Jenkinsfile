pipeline {
   agent none
   stages {
      stage('Build Docker image') {
         agent {
                dockerfile {
                  filename 'Dockerfile.build'
                  dir 'build'
                }
}
      }
   }
}
