# commands
1. run image :- docker run [image_name]
2. build docker image :- docker build -t [image-name-to-be-created] [path-to-dockerfile] 
3. pull image from dockerhub :- docker pull [dockerhub-image]
5. list docker images :- docker images || docker image ls

## docker image creation
1. start with os (e.g. - alpine)
2. Install dependencies (e.g. - nodejs)
3. copy app files
4. Run application (node app.js)