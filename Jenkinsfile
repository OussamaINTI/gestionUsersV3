node {

stage('SCM'){
 git 'https://github.com/OussamaINTI/gestionUsersV3'
 
}

stage('Compile'){
def mvnHome = tool name: 'maven-3' , type: 'maven'
sh "${mvnHome}/bin/mvn package"
}

}
