FROM centos:6
MAINTAINER "Eric Rumble"

RUN yum makecache fast \
 && yum update -y \
 && yum install -y \
        which \
 && yum clean all

CMD ["/bin/bash"]
