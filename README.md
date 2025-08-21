# LDTTeam Dev Container Features

A Visual Studio code [dev container](https://containers.dev/) features.

Installs the following command line utilities:

* [Rancher CLI](https://github.com/rancher/cli)

Auto-detects latest version and installs needed dependencies.

## Usage

Latest version installed by default. You can pin a specific version or specify latest or none if you wish to have the latest version or skip the installation. Please see below for an example:

* Rancher CLI
```
"features": {
    "ghcr.io/ldtteam/receptacula/rancher-cli:1": {
        "version": "latest"
    }
}
```