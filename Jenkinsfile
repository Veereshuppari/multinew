node('built-in') 
{
    stage('Child_Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Child_Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    }
