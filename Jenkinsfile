#!groovy
pipeline {
    agent any
    stages {
        stage('Notification') { 
            steps {
            // some instructions here
            office365ConnectorSend webhookUrl: 'https://sagportal.webhook.office.com/webhookb2/8f029912-8d5d-4e74-97cf-6cdf5c7ab666@d9662eb9-ad98-4e74-a8a2-04ed5d544db6/IncomingWebhook/e354623e72234de3a9361f463d71f66f/e95ff387-bfb9-42fc-abe6-954fb4f8a919',
            message: 'Project Repo has new check-in, start build <a href="http://localhost:8080/job/startandstopcontainer/">Link</a>',
            status: 'Success',
            color: '#0000FF'           
        }
        }
    }
}
