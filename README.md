# setup jupyter for Ubuntu 16.04

### setup

	export ENV=/tmp/.env
	virtualenv -p python3 $ENV
	. $ENV/bin/activate
	pip3 install jupyter

### use it!

	jupyter notebook

