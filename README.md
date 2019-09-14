NPF's implementation of Shinobi CCTV sofware - Running in Docker, Orchestrated by Kubernetes\
The orginal project lives [here](https://shinobi.video), but they don't recommend running the project in docker.

The unoffical docker image can be found [here](https://hub.docker.com/r/shinobicctv/shinobi/dockerfile) and we simply use this and then mounts the required volumes with kubernetes local-storage
