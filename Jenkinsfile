pipeline{
	agent any
	stages{
		stage('1-S1'){
			steps{
				sh 'cat /etc/passwd'
				sh 'whoami'
			}
		}
		stage('2-S2'){
			steps{
				sh 'lscpu'
				sh 'logname'
			}
		}
		stage('3-S3'){
			steps{
				sh 'df -h'
				sh 'touch team9'
			}
		}
		stage('4-S4'){
			steps{
				sh 'pwd'
			}
		}
		stage('5-S5'){
			steps{
				sh 'du -h'
				echo 'Welcome to Jenkins'
			}
		}
	}
}