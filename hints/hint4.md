# Hint 4
Digging for the file!

## Get the full image
We can use the the docker built-in command to export the docker image as a tar file and extract it:
```
docker save madhuakula/k8s-goat-hidden-in-layers -o hidden-in-layers.tar
tar -xvf hidden-in-layers.tar
```

## Look into a layer
We want to look into a specific layer id and check the offending file:
```
mkdir layer-files
tar -xvf blobs/sha256/<layer sha> -C layer-files
cat layer-files/root/secret.txt
```

[Back to main README](../README.md)

## Links
- [docker save](https://docs.docker.com/reference/cli/docker/image/save/)