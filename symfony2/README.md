Symfony 2 project - automatic installer script

#author			: Max Tobias Weber
#date			: 20120707
#version		: 0.1
#usage			: sudo ./symfony_project {*NEW_PROJECT_NAME*}
#==============================================================================

1.) 	Clone the latest symphony 2 version from github to a new folder 
	inside your projects directory 
2.)	wget composer.phar and install symphony bundles using
	"php composer.phar install"
3.)	Create a new vhost entry on your local apache
4.)	Create a /etc/hosts entry on your local machine
	(2) & (3) to enable browser access to the blogs dir
	using http://projectName
5.)	Create a new database
6.)	adjust /app/config/parameters.yml file
7.)	adjust folder permissions
8.)	set owner of all new files to your user account on your local machine 	(that one should also be running the apache)
9.)	restart apache web server