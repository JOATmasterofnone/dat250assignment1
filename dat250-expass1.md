#Lab Report on DAT250 EXP1


[LINK TO MY CONTAINER](https://hub.docker.com/layers/joatmasterofnone/dat250/latest/images/sha256-d40c8fd0a5a9cb683d514f8837d7e93418006d222b576bf75876f08dad9c308a?context=repo)

##Technical problems encountered during installation of the environment

Installing Gradle:
Ubuntu flags new versions of Gradle as potentially dangerous.  So when installing from snap or apt-get, Gradle version 4.4.1 is the latest you can install.  I assume gradle init wizard did not exist in this version.  I eventually decided to install from SDKman.

Installing SDKman:
The curl installation from snap in ubuntu presented errors that prevented simple installation of SDKman. The solution was to uninstall and reinstalled curl from apt-get.
    

##How I validated the environment was working
I confirmed the necessary software and the correct versions installed.
I confirmed network connection and access to the necessary websites.
I check the configuration of all the tools for development were correct 
	(i.e. access tokens, git repo configuration, dockerhub configuration)

##Pending issues that I didn't manage to solve
The app only converts to and from meters, nothing more
The logger in the app is not used
The unit tests do not perform negative testing
The app has no exception handling
The markdown file is poorly formatted


