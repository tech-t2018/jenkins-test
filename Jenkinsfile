pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "Ths will list current dir content from latest"
        ls -lh
        '''
      }
    }
  }
} 
