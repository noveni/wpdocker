# WPDocker

FOR DEVELOPPEMENT ONLY

WPDocker is Docker stack reproducing a local dev environment (LAMP) WordPress website

## WHY ?

'cause some time it's boring to setup a wordpress installation (database, transfert, unzip)

## What's included

* PHP 7.1
* MySQL 5.5
* WordPress 4.9
* phpMyAdmin

## Requirements

* Docker
* Docker-compose

## Install

WPDocker is just a set of config and tools. There is nothing to install, except Docker.

You just need to download the git repo

```sh
git clone git@github.com:noveni/wpdocker.git

cd wpdocker

bash wpd build
bash wpd start
```

Voilà

## Configurations

At root dir you'll find a ``.env`` file
You can change variables to reflect your setup.

## Usage

Start environment

```sh
bash wpb start (Like docker-compose up -d)
```

Stop environment (Like docker-compose down -v)

```sh
bash wpb stop
```

Print IP (Only on Mac OSX)

```sh
bash wpb ip
```

Attach a bash shell on the wordpress container

```sh
bash wpb bash
```

## TODO

* make executable
* add help cmd
* add wp-cli