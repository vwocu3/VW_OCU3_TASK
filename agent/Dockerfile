FROM jenkins/ssh-agent:latest-jdk11
# #jenkins/ssh-agent:latest-alpine-jdk11
# # Install maven
# USER root
# RUN apt-get update && apt-get install -y wget

# # get maven 3.2.2
# RUN wget --no-verbose -O /tmp/apache-maven-3.2.2.tar.gz http://archive.apache.org/dist/maven/maven-3/3.2.2/binaries/apache-maven-3.2.2-bin.tar.gz

# # verify checksum
# RUN echo "87e5cc81bc4ab9b83986b3e77e6b3095 /tmp/apache-maven-3.2.2.tar.gz" | md5sum -c

# # install maven
# RUN tar xzf /tmp/apache-maven-3.2.2.tar.gz -C /opt/
# RUN ln -s /opt/apache-maven-3.2.2 /opt/maven
# RUN ln -s /opt/maven/bin/mvn /usr/local/bin
# RUN rm -f /tmp/apache-maven-3.2.2.tar.gz
# ENV MAVEN_HOME /opt/maven