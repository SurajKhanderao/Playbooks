you can creates playbooks using ansible-galaxy init role_name or You can create your custom roles using dir1/tasks/main.yml

For Tomcat
remember for tomcat if you have changes any file inside that tomcat dir make sure you restart tomcat like you have changed user file also all other file like context.xml you need to restart tomcat if it not restart after playbook runs...this is because we not given notifyer after that task...so keep the notifyer after those tasks which chnages config of tomcat
