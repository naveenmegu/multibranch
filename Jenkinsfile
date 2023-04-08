pipeline {
    agent any

    stages {
        stage('Stage1:SCM CHECKOUT') {
            steps {
                echo "THis is Checkout Stage"
                sh 'sleep 5'             
            }
        }
        stage('Stage2:BUILD') {
            steps {
                echo 'This is Build Stage'
                sh 'sleep 5'
            }
        }
        stage('Stage3:Push') {
            steps {
                echo 'This is push Stage'
                sh 'sleep 5'
            }
        }
		stage('Stage4:Deploy') {
            steps {
                echo 'This is Deploy Stage'
                sh 'sleep 5'
            }
        }
		stage('Stage5:Test') {
            steps {
                echo 'This is test Stage'
                sh 'sleep 5'
            }
        }
    }
}    
