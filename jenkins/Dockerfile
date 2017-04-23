FROM jenkins

USER root
RUN apt-get update && apt-get install -y docker
RUN usermod -G docker jenkins
USER jenkins
