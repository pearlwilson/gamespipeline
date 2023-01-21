pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Let us play the game pipeline'
            }
        }
        stage('game') {
            steps {
                echo 'This is the first Game on the pipeline'
                sh 'python guessnumber.py'
            }
        }
	stage('game') {
            steps {
                echo 'This is the second Game on the pipeline'
                sh 'python tictactoe.py'
            }
        }
	stage('game') {
            steps {
                echo 'This is the third Game on the pipeline'
                sh 'python Quiz Game Avengers.py'
            }
        }	
	stage('game') {
            steps {
                echo 'This is the third Game on the pipeline'
                sh 'python Quiz Game Cartoons.py'
            }
        }	
    }
}
