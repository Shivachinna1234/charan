node {

     stage('gitclone') {
            git branch: 'main', credentialsId: 'venky', url: 'https://github.com/Shivachinna1234/charan.git'

    }
    stage('java version') {

         sh 'java -version'

    }
    stage('maven version') {

         sh 'mvn -version'

    }
    stage ('maven validate') {
         sh 'mvn validate'
    }
	stage('maven compile') {

         sh 'mvn compile'
    }
    stage('maven test') {

         sh 'mvn test'

    }
    stage('maven package') {

         sh 'mvn package'
    }
    stage('maven deploy') {

         sh 'mvn deployment'
    }
    
    }


