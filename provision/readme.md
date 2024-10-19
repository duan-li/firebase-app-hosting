## Firebase container

### docker container
```
docker run -it --rm -p 8800:8800 -p 8080:8080 -p 4400:4400 -p 9005:9005 -v $(pwd):/tmp/filebase ubuntu:24.04 /bin/bash

docker run -it --rm -p 4200:4200 -p 3000:3000 -v $(pwd):/work node:20 /bin/bash
```

### install firebase-tools

```
apt update
apt install -y nodejs node-gyp npm
sudo npm install -g firebase-tools
npm add --global nx@latest
firebase help
```

### filebase init

```
firebase login

firebase apphosting:backends:create --project PROJECT_ID --location us-central1
# example
firebase apphosting:backends:create --project liduan-blog --location us-central1

firebase apphosting:backends:delete --project liduan-blog firebase-auth-page

```
