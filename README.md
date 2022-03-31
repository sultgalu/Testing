# DOCKER
## PART1
run following commands from **contextdir**:
```powershell
docker build -t myimage .
```
```powershell
docker run -dit --mount type=bind,source="${PWD}\shared",target=/win --name apache-app myimage
```
