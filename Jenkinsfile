pipeline {
    agent any

    triggers {
        scm '*/5 * * * *' // Poll SCM every 5 minutes (for testing purposes)
    }

    stages {
        stage('Trigger Check') {
            steps {
                echo 'Pipeline triggered by a Git push (or SCM polling)!'
            }
        }
    }
}
