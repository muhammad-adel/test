pipeline {
   agent none
   stages {
      stage (Build Docker iamge){
         agent {
            docker {
                dockerfile {
                  filename 'Dockerfile.build'
                  dir 'build'
                  label 'my-defined-label'
                  additionalBuildArgs  '--build-arg version=1.0.2'
                 args '-v /tmp:/tmp'
    }
}
}
      }
   }
}
