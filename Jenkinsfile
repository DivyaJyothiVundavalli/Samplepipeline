pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the specified repository
                git url: 'https://github.com/DivyaJyothiVundavalli/StockWatch.git', branch: 'main'
            }
        }
        stage('Confirm Checkout') {
            steps {
                // List the files to confirm checkout
                bat 'dir'
                
                // Optionally, you can view the content of a specific file
                bat 'type  testresult.txt'
            }
        }
    }
}
