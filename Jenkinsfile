pipeline {
    agent any
    
    parameters {
   
    	string(name:'BranchName',
      	defaultValue: 'master!',
      	description: 'enter your branch name')
  }
    stages {

        stage('build th app'){ 
            steps {
            sh 'mvn clean '
             echo 'Test for Tah'
                
            }
        }
    }
}