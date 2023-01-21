pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Let us play the game pipeline'
            }
        }
        stage('game1') {
            steps {
                echo 'This is the first Game on the pipeline'
                sh 'python guessnumber.py'
            }
        }
	stage('game2') {
            steps {
                echo 'This is the second Game on the pipeline'
                sh 'python tictactoe.py'
            }
        }
	stage('game3') {
            steps {
                echo 'This is the third Game on the pipeline'
                sh 'python Quiz Game Avengers.py'
            }
        }	
	stage('game4') {
            steps {
                echo 'This is the third Game on the pipeline'
                sh 'python Quiz Game Cartoons.py'
            }
        }	
    }
}
