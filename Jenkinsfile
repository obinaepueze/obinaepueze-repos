pipeline{
	agent any 
	stages{
		stage('1-write your name'){
			steps{
				sh 'echo "my name is Simione"'
			}
		}
		stage('2-make a directory'){
			steps{
				sh 'mkdir simione'
			}
		}
		stage('3-check memory free space'){
			steps{
				sh 'free -m'
			}
		}
		stage(3-'check the disk'){
			steps{
				sh 'lsblk'
			}
		}
	}
}
