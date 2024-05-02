# Hint 3
[dive](https://github.com/wagoodman/dive) is an amazing tool that helps with analyzing each layer of an image.
```
dive madhuakula/k8s-goat-hidden-in-layers
```
Tips:
- use arrow to move up and down
- use tab to switch to the file explorer
- use space to collapse folders

[Back to main README](../README.md)

## Troubleshooting
if you get issues fetching the image re-reun the alias command:
```
alias dive="docker run -ti --rm  -v /var/run/docker.sock:/var/run/docker.sock wagoodman/dive"
```

## Links
- [dive](https://github.com/wagoodman/dive)