pipeline {
         agent any
         stages {
                 stage('Clone') {
                 steps {
		    git branch: "*/main",url: "https://github.com/saurabh509/Jenkins.git", credentialsId: "d04ccce0-cb33-4aca-9bc2-d12c4f3a2d5e	"
		    sh 'ls -lrt'
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
