# Linux-performance-monitoring
Linux performance monitoring built on docker
# Constructing
# execute the following commands
docker build --network host -f base.dockerfile .
cd /home/jpd/work/private-node/docker/scripts
./monitor_docker_run.sh
./monitor_docker_into.sh
#  Compile
cd work
cd cmake
cmake ..
make
