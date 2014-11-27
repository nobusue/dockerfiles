FROM centos:centos6
MAINTAINER Nobuhiro Sue <nsue@e-mail.ne.jp>
RUN curl -LO 'http://download.oracle.com/otn-pub/java/jdk/7u72-b14/jdk-7u72-linux-x64.rpm' -H 'Cookie: oraclelicense=accept-securebackup-cookie' \
      && rpm -i jdk-7u72-linux-x64.rpm \
      && rm jdk-7u72-linux-x64.rpm
ENV JAVA_HOME /usr/java/latest
