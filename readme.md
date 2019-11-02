## Tommy's test jenkins placeground for jenkinsfiles and so on.

docker-compose up

# Clean up:
docker-compose down
docker-compose kill
rm -r var/jenkins_home/* #; rm -rf var/jenkins_home/.java


# To try: adding chef
https://ringo.de-smet.name/2015/03/keep-chef-out-of-your-docker-containers/
https://supermarket.chef.io/cookbooks/docker

# Unit testing for jenkins:
https://github.com/jenkinsci/JenkinsPipelineUnit

# Run jenkinsfiles locally:
https://github.com/jenkinsci/jenkinsfile-runner