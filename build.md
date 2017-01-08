To build a new image,

(Get the root priviliges for using docker correctly)
Pull the latest image using:
```
docker pull golang
```

Build the image from a dockerfile using
```
docker build -t battery-historian .
```

Tag the image using
```
docker tag #hashid bhaavan/battery-historian:latest
```

Then login into docker and push the image
```
docker pull bhaavan/battery-historian
```
