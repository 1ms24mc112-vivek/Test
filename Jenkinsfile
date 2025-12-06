pipeline {
    agent any
    triggers {
          pollSCM("* * * * *")
    stages{
      stage('Checkout'){
        steps {
            git branch: 'main', url: 'https://github.com/1ms24mc112-vivek/Test.git'
             }
        }
    stage('Build'){
        steps {
            echo "Building..."             }
        }    
    stage('git'){
        steps {
            echo "changes made..."             }
        }
    stage('Test'){
        steps {
            echo "Testing..."        
             }
        }
    }
}
