pipeline{
 agent {label "maven-agent"}
<<<<<<< Updated upstream
 tools{
   maven "M3"
   kubectl "K3"
 }
=======
   tools{
     docker "D3"
   }
>>>>>>> Stashed changes
    stages{
      stage("prep"){
        echo "hello wolrd"
        git  "https://github.com/devopsgsvc/gsvccore.hgit"
        sh "mvn clean deploy"
      }
      stage('build'){
        echo "building applications"
      }
      stage('deploy'){
        echo "building applications"
      }
    }
}
