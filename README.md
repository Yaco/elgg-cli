CLI Tools for Elgg
==================
![Elgg 2.2](https://img.shields.io/badge/Elgg-2.2-orange.svg?style=flat-square)

## Installation

```sh
cd /path/to/elgg/

composer require hypejunction/elgg-cli:dev-master
```

## Run Commands

```sh
cd /path/to/elgg/

# Get help
vendor/bin/elgg-cli --help

# List all commands
vendor/bin/elgg-cli list

# Add a new user
vendor/bin/elgg-cli user:add [--admin] [--notify] <username> <name> <email>

# Display or change site URL
vendor/bin/elgg-cli site:url <new_url>

# Display or change root path
vendor/bin/elgg-cli config:path <new_path>

# Display or change data directory path
vendor/bin/elgg-cli config:dataroot <new_path>

```

## Compiling a new build

To compile a new build, you first need to install box:

```sh
composer global require kherge/box --prefer-source
```

