pipeline {
    agent any
    stages {      
        stage('CI') {
            parallel {
                
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
