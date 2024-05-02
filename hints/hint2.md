# Hint 2
We can use the `dfimage` to generate a Dockerfile of any given image.
```
dfimage madhuakula/k8s-goat-hidden-in-layers
```
[Back to main README](../README.md)

## Troubleshooting
If the command is not found, run:
```
alias dfimage="docker run -v /var/run/docker.sock:/var/run/docker.sock --rm ghcr.io/laniksj/dfimage"
```

## Links
- [dfimage](https://github.com/LanikSJ/dfimage)