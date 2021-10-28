https://github.com/Surian/sensu-go-docker 

https://hub.docker.com/r/surian/sensu-go

rip but so small just copied to modify and not fork

Dockerfile to provide Sensu Go backend and agent compiled from open-source version of Sensu Go  https://github.com/sensu/sensu-go).

From version 5.15.0, binaries provided by Sensu have commercial features enabled by default but is limited to 100 entities.


Build
```
$ sudo docker build . --build-arg SENSU_VERSION=5.16.1
```
