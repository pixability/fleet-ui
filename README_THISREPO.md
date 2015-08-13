* use ws: or wss: protocoal based on the client calls. 
* use debian:jessie base image. The busybox's openssh-client-utils breaks with missing shared libs (error:ssh-agent not found).
* to buid
```
git clone  https://github.com/xuwang/docker-fleetui-builder.git
cd docker-fleetui-builder
./build.sh github.com/xuwang/fleet-ui
```
