pipeline {
         agent any
         stages {
                 stage('Clone') {
                 environment {
			  MY_FILES = sh(script: 'cd mydir && ls -l', returnStdout: true)
			}
			steps {
			  sh '''
			    echo "$MY_FILES"
			  '''
			}
                 }
                 stage('Build') {
                 steps {
                    echo('Sample testing of Stage 2')
                 }
                 }
                 stage('Deploy') {
                
                 steps {
                       echo 'Thanks for using Jenkins Pipeline'
                 }
                 }
              }
}
