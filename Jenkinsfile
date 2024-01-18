pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'dotnet build eShopOnWeb.sln'
      }
    }

    stage('Tests') {
      steps {
        sh 'dotnet test tests/UnitTests'
      }
    }

  }
}