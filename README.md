tmpvirtualenv
=====

tmpvirtualenv is a small and easy-to-use lightweight tool that allows users to create a virtual environment to install all dependencies they need in order to run third-party source code, even without the presence of a requirements file. tmpvirtualenv also allows one to percolate certain libraries installed on the virtual environment into their main environment. 

##Example Use
To create a virtual environment and work on it:
```
	tmpvirtualenv directoryOfSourceCode
```
To percolate a module:
```
	tmpvirtualenv -p package1 [package2 package3...]
```

