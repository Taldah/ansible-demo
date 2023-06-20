FROM ubuntu
RUN apt update && apt install python3-pip vim git -y && pip install ansible 
#RUN apt-get update &&\
#    apt-get install vim -y && \
#    apt-get install openssh-server -y && \
#    mkdir /var/run/sshd && \
#    apt-get install python3-pip -y && \
#    pip3 install --upgrade pip &&\
#    pip3 install --upgrade virtualenv && \
#    pip3 install ansible 
RUN mkdir /etc/ansible
RUN echo [servers] > /etc/ansible/hosts && \
    echo node1 >> /etc/ansible/hosts
#EXPOSE 22
#CMD ["/usr/sbin/sshd", "-D"]
