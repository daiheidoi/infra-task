FROM centos:7

# update yum
RUN yum update -y && \
    yum clean all
# epelをインストール
RUN yum -y install epel-release
# Remiをインストール
RUN yum -y install http://rpms.famillecollet.com/enterprise/remi-release-7.rpm
# httpd, sshd, scp, openssl, sudo, which
RUN yum -y install httpd httpd-tools openssh-server openssh-clients openssl sudo which
# PHP7.3をインストール
RUN yum -y install --enablerepo=epel,remi,remi-php73 php php-{devel,mbstring,pdo,gd,xml,mcrypt,mysqlnd}

EXPOSE 80
CMD ["/usr/sbin/httpd", "-DFOREGROUND"]