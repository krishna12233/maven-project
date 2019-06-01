pipeline {
    agent any
    tools { 
        maven "localMaven"
    }   
    stages{
        stage('Build'){
            steps{
               sh 'mvn clean package'
                   echo "PATH = ${PATH}"
                   echo "M2_HOME = ${M2_HOME}"
          }
}
}
}
