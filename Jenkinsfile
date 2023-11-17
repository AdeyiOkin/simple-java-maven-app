pipeline {
    agent any

    stages {
  stage('build') {
    steps {
      echo 'Building'
    }

    tools {
      maven 'Maven3'
    }
  }

  stage('test') {
    steps {
      echo 'Testing'
    }
  }

  stage('deploy') {
    steps {
      echo 'Deploying'
    }
  }

}
}
