docker run \
  -p 8081:8080 \
  -p 50000:50000 \
  --name my-jenkins \
  -v jenkins_data:/home/jmalmeida/jenkins_home \
  jenkins/jenkins:lts

Copy the password and go to http://localhost:8081 to do the initial setup.

Paste the administrator password and continue. The setup process will give you the choice to customize the plugins you want to add. Choose Install Suggested Plugins and continue. Wait for the installation to complete.

