pipeline {
  agent any
  stages {
    stage ("compile"){
      steps{ 
       git "https://github.com/Jagadheeswar-advantest/sampleproject.git"
          }
    }
      stage ("build"){
        steps {
          sh "mvn clean package" 
        }
      }
    stage ("test"){
      steps {
    echo "this is a testing stage" 
      }
    }
}
}
