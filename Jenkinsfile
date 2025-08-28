pipeline {
  agent any
  stages {
    stage('Checkout') { steps { checkout scm } }
    stage('Build')    { steps { sh 'echo building' } }
    stage('Test')     { steps { sh 'echo testing' } }
    stage('Package')  { steps { sh 'echo packaging' } }
  }
}
