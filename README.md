# webapp-ansible

## Deploy an apache container

- Create a cluster (1 ansible and 1 client)
- Create a webapp folder that will contain all the files of our project
- Create an inventory file called prod.yml (in yaml format) containing a prod group with our client as the only
member our client
- Create a group_vars folder that will contain a file named prod that will contain the login information to be used by
used by ansible (login and password)
- Create a playbook named deploy.yml allowing to deploy apache with docker on the client (the image to use is httpd and the port to use is
image to use is httpd and the port to expose to the outside is 80)
- You have the right to install any prerequisite you deem necessary using the yum module
- Check the syntax of your playbook with the ansible-lint command (install it if it is not available)
- Check that after running your playbook the default apache site is available on port 80
- Explore the ansible debug options
- In order to keep your work, push it to your github
