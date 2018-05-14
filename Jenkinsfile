pipeline {
  agent any
  stages {
    stage('First Stage') {
      agent any
      environment {
        Foo = 'World'
      }
      steps {
        echo "Hello ${FOO}"
      }
    }
  }
}