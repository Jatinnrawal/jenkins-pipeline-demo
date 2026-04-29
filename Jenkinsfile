pipeline {
    agent any
	

    stages {


	stage('Install Dependencies') {
		steps {
			bat 'pip install pytest'
		}
	}


	stage('Test') {
		steps {
			bat 'pytest'
		}
	}


        stage('Run App') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
