DevOps Test Code Repository

Ansible script for DevOps test

Purpose: 

Task M#1
To create ansible deployment script to deploy MySQL and nginx as well as DjangoCMS and upload the finished script on GitHub for review.
Task parameters:
	- Playbook should install mysql, nginx.
	- CMS should start under newly created user.
	- Playbook should put installed test DjangoCMS application code into new repository on Github

Task M#2
To create backup script and backup rotation schedule with specific parameters:
	- Put configs and mysql dump to /backup/
	- Keep only 7 successful backups
	- Only backup when server load is less than 2
Upload finished script to GitHub, along with workflow, for review.
