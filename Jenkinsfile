node('master') {
  stage ('Node Check') {
    sh 'hostname -i'
    sh 'whoami'
    checkout scm
    sh 'pwd'
  }
}

node('jdc-slave') {
  stage ('Node check') {
    sh 'hostname -i'
    sh 'whoami'
//    checkout scm
    sh 'pwd'
  }
} 
