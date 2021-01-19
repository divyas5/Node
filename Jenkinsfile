pipeline {
    agent test_node 
    stages {
        stage('git') { 
            steps {
               git url: 'https://github.com/divyas5/Node.git'
               bat 'git.bat'
          
            }
        }
    }
}
