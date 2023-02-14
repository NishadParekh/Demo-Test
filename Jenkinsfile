node {
  stage ('checkout code from git hub') {
    git branch: 'main', url: 'https://github.com/NishadParekh/Demo-Test.git'
  }
  stage ('executing shell script') {
    sh "sh mem.sh"
  }
  stage ('content in the ') {
    sh "cat demo.html"
  }        
}
