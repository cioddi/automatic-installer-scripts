Wordpress - automatic installer script

#author			: Max Tobias Weber
#date			: 20120705
#version		: 0.1
#usage			: sudo ./wordpress_project {*NEW_PROJECT_NAME*}
#==============================================================================

1.) Download and unpack the latest worpress release from
	www.wordpress.org/latest.zip to a new folder inside 
	your projects directory 
2.)	Create a new vhost entry on your local apache
3.)	Create a /etc/hosts entry on your local machine
	(2) & (3) to enable browser access to the blogs dir
	using http://blogName
4.)	Create a new database
5.)	adjust and rename wordpress config file
6.)	adjust folder permissions
7.)	set owner of all new files to your user account on your
 	local machine (that one should also be running the apache)

USAGE:
1.) edit variables in wordpress_project.sh (once)
2.) sudo ./wordpress_project [_PROJECTNAME_]
3.) goto http://[_PROJECTNAME_] in your browser and finish the installation