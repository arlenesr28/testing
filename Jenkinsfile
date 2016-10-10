#!groovy

node {
	//stage 'Instalando python en el ambiente virtual'
	//sh 'python setup.py install'
	//echo 'Instalando python...'
	
	//stage 'Preparando ambiente'
	//sh 'PYENV_HOME=$WORKSPACE/.pyenv/'
	//if [ -d $PYENV_HOME ]; then
    	//	sh 'rm -rf $PYENV_HOME'
	//fi
	
	//sh 'virtualenv --no-site-packages $PYENV_HOME'
	//sh '. $PYENV_HOME/bin/activate'
	stage 'Checkout source master'
	git url: 'git://github.com/arlenesr28/testing.git',
	//	branch: 'master'

	checkout scm 
	echo 'configuracion scm de dos branches'
	//checkout([$class: 'GitSCM', branches: [[name: '*/master'],[name: '*/QA']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '593d0524-8364-4335-89d3-fc0bed5ed382', url: 'https://github.com/arlenesr28/testing.git']]])
	//echo 'configuracion scm de dos branches'
}
