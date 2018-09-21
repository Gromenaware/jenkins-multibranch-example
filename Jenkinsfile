pipeline {
    agent any
    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean compile'
            }
        }
        stage ('Testing Stage') {
            steps {
                    sh 'mvn test'
            }
        }
        stage ('Deployment Stage') {
            steps {
		    echo 'Deploying the app'
		    echo 'Finished deployed'
            }
        }
    }
}
