pipeline {
    agent any
	

    stages {


	stage('Install Dependencies') {
		steps {
			bat 'pip install pytest'
		}
	}



        stage('Run Flask App') {
            steps {
                bat 'start cmd /k python app.py'
            }
        }
    }
}
