node('Built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/M-Yermiah/CI_CD.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
