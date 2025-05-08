pipeline {
    agent any

    triggers {
        cron '*/5 * * * *' // Trigger every 5 seconds (use with caution!)
    }

    stages {
        stage('Hello') {
            steps {
                echo 'hello world'
            }
        }
    }
}
