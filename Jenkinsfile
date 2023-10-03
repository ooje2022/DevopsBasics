node{
  stage('SCM Checkout'){
    git 'https://github.com/ooje2022/DevopsBasics'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
