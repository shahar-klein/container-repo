# container-repo

Create  a repo and run in container

docker run -v /packages/:/repo -p 8080:8000 con-repo


set:
[ovs-cicd]
name=sdn-ovs-cicd
baseurl=http://10.8.51.104:8080/ovs
gpgcheck=0
enabled=1

