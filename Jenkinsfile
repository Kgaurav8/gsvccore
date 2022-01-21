pipeline{
 agent {label "maven-agent"}
 tools{
   maven "M3"
   kubectl "K3"
 }
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
