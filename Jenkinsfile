node {
  stage ('checkout') {
    git 'git@github.com:leenajob/my-awesome-project.git'
  }
  stage('run script') {
  sh "./say_hello.sh"
}
}
