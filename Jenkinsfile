pipeline {
     agent any
     stages {
        stage("checkout") {
            steps {
  checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'Git_jenkins', url: 'https://github.com/raghavendra321/testingapp.git']]])
  
	}
	
	}
stage('build')
{
    steps
    {
       bat 'mvn package'
    }
}
}
}
