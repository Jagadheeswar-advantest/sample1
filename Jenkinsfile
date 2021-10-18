pipeline {
  agent any
  stages {
    stage ("compile"){
      steps{ 
       git clone https://github.com/Jagadheeswar-advantest/sampleproject.git
          }
    }
      stage ("build"){
        steps {
          mvn clean package 
        }
      }
    stage ("test"){
      steps {
    echo "this is a testing stage" 
      }
    }
}
}
