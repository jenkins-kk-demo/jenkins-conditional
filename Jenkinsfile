pipeline {
    agent any

    stages {
        stage('Hello') {
            when {
                  changeRequest()
                }

                steps {
                    echo 'Exploring the when condition'
                }
        }
    }
}
