pipeline {
    agent any
    tools { 
        maven 'Maven 3.3.9'
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
