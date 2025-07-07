pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "building step"
            }
        }
        stage('Groovy stage') {
            steps {
                script {
                    def course="ks8"
                    if (course == "ks8")
                        println("thanks for enrolling")
                    else
                        println("Do enroll for ks8")
                        //println("print the condition $(course) course")
                }
            }
        }
    }
}
