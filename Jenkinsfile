pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/kavyashree123-ops/new.git',
            branch: 'main'
      }
    }

    stage('Run Shell Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
