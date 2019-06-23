pipeline {
    agent any
    stages {

        stage('tomcat install'){
          steps{
		    echo 'tomcat install from Jenkins through Git'
                //sh 'mkdir from-jenkins'
                //sh 'touch from-jenkins/test.txt'
		    echo 'running palybook' 
                sh '''
                   ansible-playbook -i hosts myplay.yml 
                '''
                }
        }

}
}

