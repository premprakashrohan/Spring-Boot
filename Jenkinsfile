pipeline {
  agent any
  stages {
    stage('one') {
      steps {
        build(job: 'spring boot', quietPeriod: 1)
      }
    }
  }
}