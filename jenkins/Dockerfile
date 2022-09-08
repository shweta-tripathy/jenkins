FROM httpd
RUN yum install httpd -y
RUN git clone https://github.com/shweta-tripathy/jenkins.git
WORKDIR jenkins
RUN cp jenkins/index.html /var/www/html/
RUN systemctl start httpd
