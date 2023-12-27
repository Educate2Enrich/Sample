pipeline {
   agent any
   stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github-sample', url: 'https://github.com/Educate2Enrich/Sample.git']]])
                sh "ls -lart ./*"
            }
        }
    }
}
