pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        echo "This should run on the BUILD stage"
        echo "Second step on BUILD"
      }
    }
    stage('Test') {
      steps {
        echo "This is a TEST stage step"
        echo "Just one more dummy step"
        echo "Adding garbage"
      }
    }
    stage('Deploy') {
      steps {
        echo "Drinking a coffee while the deploy runs"
        echo "Deploy is taking to long, ordering a pizza..."
	echo "kenny master was here, nobody could beat me!!"
        echo "This is a DEPLOY stage step"
        echo "hello everybody!"
      }

}
  }
}
