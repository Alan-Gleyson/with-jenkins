pipeline {
	/* onde executa */
	agent any

	/* Onde o trabalho acontece*/
	stages {

		stage("build") {

			steps {
				echo 'building the application'
			}

		}

		stage("test") {
			
			steps {
				echo 'testing the application'	
			}
		
		}

		stage("deploy") {

			steps {
				echo 'deplying the application'
			}
		}
	}
}
