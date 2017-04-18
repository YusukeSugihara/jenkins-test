node {
  stage ('Node Check') {
    sh 'hostname -i'
    sh 'whoami'
  }
}

node('jdc-slave') {
  stage ('Node check') {
    sh 'hostname -i'
    sh 'whoami'
  }
} 
