node('Dockernode')
 {
  stage('source code')
   {
    git 'https://github.com/wakaleo/game-of-life.git'
   }
  stage('creating artifact')
   {
    sh 'mvn package'
    }
  }