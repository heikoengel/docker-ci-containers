FROM cern/cc7-base
RUN rpm --rebuilddb
RUN yum clean all && yum install -y pciutils-devel numactl-devel kmod-devel kernel-devel git gcc
