node{
  stage('SCM Checkout'){
    git 'https://github.com/ooje2022/devopsBasics'
  }
  stage('Compile-Package'){
    sh 'mnv package'
  }
}
