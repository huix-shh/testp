pipeline{
  agent any
  stages{
    stage("first") {
      steps {
        echo 'hello,world'
      }
    }
  }

  post{
    always{
      echo 'finished'
    }
  }
}
