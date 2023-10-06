Jenkins:
------------------------

It is ci/cd tool

CI - Continous Integration is an orchestration server, it can connect with any external tools or systems if you have that plugin/command installed.

with the help of plugins we can enable or disable the functionality.

install plugin --> you will get features

uninstall plugin --> your features will be removed

CI server is nothing but a server, which has jenkins installed.

CI process
-------------
develop --> build(compile) --> scan the code --> create a package --> push to S3/nexus

CI --> continous integration
CD --> continous deployment

Jenkins has UI, Backend, DB(file system)

wherever we store the data we can call it as a database.

Two type of Jobs:
-------------------------
1. Freestyle is UI based, can't restore easily, cant trace who did the changes, no version control

2. pipeline

	keep in git,
	version control,
	restore,
	review the changes

    