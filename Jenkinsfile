tools { 
    maven 'Maven3' 
} 
 
stage('Verify Maven') { 
    steps { 
        bat 'mvn -version' 
    } 
} 
 
stage('Maven Build') { 
    steps { 
        bat 'mvn clean install' 
    } 
}
