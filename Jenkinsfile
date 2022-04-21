pipeline{
agent any
tools{
	maven 'M3'
}
stages{
	stage('Checkout'){
		steps{
			git 'https://github.com/Harish1000/Demo2.git'
		}
	}
	stage('Build'){
		steps{
			bat 'mvn clear compile'
		}
	}
}
}
