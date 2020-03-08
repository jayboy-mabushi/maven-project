FROM centos7

RUN yum install openssh-server -y

RUN useradd remote_user && \
    echo "school1" | passwd remote_user --stdin
    mkdir /home/remote_user/.ssh && \
    chmod 700 /home/remote_user/.ssh

