node(){
    stage("clone"){
        checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/csenapati12/java-tomcat-maven-docker.git']]]
        echo "clone"
    }
     stage("maven build"){
        sh label: '', script: 'ls'
    }
     stage("docker"){
         sh label: '', script: 'ls'
        echo "docker"
    } 
    stage("deploy"){
        echo "deploy"
    }
}
