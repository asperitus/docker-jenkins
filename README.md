# docker-jenkins

git clone https://github.com/asperitus/jenkins.git
cd jenkins
git remote rename origin github
git remote add origin git@[hostname]:[owner]/jenkins.git
git push -u origin master