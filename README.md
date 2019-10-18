# netcore-node-azure-func-container

A Debian 9 container including .net core sdk, node.js and azure functions CLI

[netcore-node-azure-func-container on Docker Hub](https://cloud.docker.com/repository/docker/loige/netcore-node-azure-func-container)


## Usage

To run the container interactively:

```bash
docker run -it loige/netcore-node-azure-func-container
```

If you want to use this as a base image:

```Dockerfile
FROM loige/netcore-node-azure-func-container

# add your new layers here
```


## Contributing

Everyone is very welcome to contribute to this project. You can contribute just by submitting bugs or
suggesting improvements by [opening an issue on GitHub](https://github.com/lmammino/netcore-node-azure-func-container/issues).

You can also submit PRs as long as you adhere with the code standards and write tests for the proposed changes.


## License

Licensed under [MIT License](LICENSE). © Luciano Mammino.
