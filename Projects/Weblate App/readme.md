**Weblate App Deployment**

#to deploy specfic version of weblate app
- ansible-playbook deploy.yml -e "weblate_version=4.1-2"

#to deploy latest version of weblate app
- ansible-playbook deploy.yml                                
