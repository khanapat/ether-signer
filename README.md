# EthSigner

A transaction signing application to be used with a web3 provider. All questions, queries and other discussion can be found on [Discord].

## Issues

EthSigner issues are tracked in [GitHub issues].

See our [contribution guidelines](CONTRIBUTING.md) for more detail on searching and creating issues.

## Users

-   [User documentation](https://docs.ethsigner.consensys.net/)

## Chat

-   [Discord]

## Developers

-   [Contribution Guidelines](CONTRIBUTING.md)
-   [Coding Conventions](CODING-CONVENTIONS.md)

## Release Notes

-   [Release Notes](CHANGELOG.md)

[discord]: https://discord.gg/jCk2XuYtrp
[github issues]: https://github.com/ConsenSys/ethsigner/issues

## how to build

[gradle build] : ./gradlew build

## after finish build

[unpack ethsigner-develop.tar.gz] unpack file ethsigner-develop.tar.gz using command -> tar -xzf ethsigner-develop.tar.gz

# docker

[docker build] : docker build -f docker/Dockerfile -t ethsigner:1.0.0 --build-arg VERSION=1.0.0 .
[docker login] : docker login -u <user-name>
[docker push] : docker tag && docker push

# ref

-   https://consensys-ethsigner-v0ih6cvlwfp.ws-us93.gitpod.io/
