pipeline {
    agent any
    stages {
        stage("First Stage") {
            steps {
                echo "This staged run on the Build run"
                echo "Second step on build"
            }
        } 
        step("Test") {
            steps {
              echo "This is a Test staged step"
            }
        }
        step("Deploy") {
          steps {
              echo "This is a Deploy staged step"
            }
        } 
    }
}   
      
