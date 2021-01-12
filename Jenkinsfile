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
    stage('archiving artifacts')
    {
     archiveArtifacts artifacts: '/home/jenkins/workspace/Pipeline/gameoflife-web/target/*.war',      followSymlinks: false
    }  
   }