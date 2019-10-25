node {
	stage('1'){
		echo 'one'
	}
	stage('script'){
		echo 'running script'
		git 'https://github.com/lalitbhattgit/newrepo'
		sh 'chmod +x script.sh'
		sh './script.sh'
	}
}
