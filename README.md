Docker for WHMCS
===

A WHMCS 7.1+ developer environment for docker/docker-compose which is heavily inspired by [Laradock](https://github.com/laradock/laradock/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

Clone this repo with git and copy the _[WHMCS](https://download.whmcs.com/ "Download Page")_ installation archive to the `./whmcs` directory.



### Requirements

You need a valid and licensed copy of WHMCS 7.1+.
If needed, you can ask the WHMCS Support for a Developer License.

## Usage

Copy the `env-example` to `.env` and edit the parameters if you want too.

Keep in mind, you need to choose the right php version for your WHMCS Installation.

**Example:** WHMCS 7.1 needs PHP 7.0 while Version 7.2 requires PHP 7.1+

Start the container with

```
docker-compose up
```

If you have change the networking

```
docker-compose up --force-recreate
```


After building the container, open your browser and browse to the `/install` directory and install it.

WHMCS installation itself may take a while.

### Development License

If you need a seperate License for your WHMCS installation, you can ask the WHMCS Support for a development license.

## Contributions

Please use [Github](https://github.com/darthsoup/docker-whmcs) for reporting bugs, and making comments or suggestions.
