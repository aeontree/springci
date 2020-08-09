FROM jenkins/inbound-agent

USER root

RUN apt-get update && apt-get upgrade
RUN apt-get install -y maven



USER jenkins

COPY text.txt /home/jenkins/text.txt

# CMD ["cat", "/home/jenkins/text.txt"]
CMD ["cat",  "text.txt"]