pipeline {
    agent any
    stages {      
        stage('CI') {
            parallel {
                stage('project 1') {
                    stages {
                        stage('Test') {
                            steps {
                                echo "Build"
                            }
                        }
                        stage('Build') {
                            steps {
                                echo "Build"
                            }
                        }
                        stage('Deploy (Staging)') {
                            steps {
                                echo "Deploy (Staging"
                            }
                        }
                        stage('Manual Approval') {
                            steps {
                                echo "Deploy (Staging"
                            }
                        }
                        stage('Deploy (Production)') {
                            steps {
                                echo "Deploy (Production)"
                            }
                        }   
                    }
                }
                stage('project 2') {
                    stages {
                        stage('Test') {
                            steps {
                                echo "Build"
                            }
                        }
                        stage('Build') {
                            steps {
                                echo "Build"
                            }
                        }
                        stage('Deploy (Staging)') {
                            steps {
                                echo "Deploy (Staging"
                            }
                        }
                        stage('Manual Approval') {
                            steps {
                                echo "Deploy (Staging"
                            }
                        }
                        stage('Deploy (Production)') {
                            steps {
                                echo "Deploy (Production)"
                            }
                        }   
                    }
                }
            }
        }
    }
}
