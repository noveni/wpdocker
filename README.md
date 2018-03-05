# WPDocker

WPDocker is Docker stack reproducing a local dev environment (LAMP) WordPress website

## What's included

* PHP 7.2
* MySQL 5.5
* WordPress 4.9
* phpMyAdmin

## Install

WPDocker is just a set of config and tools. There is nothing to install, except Docker.

You just need to download the git repo

```sh
git clone git@github.com:noveni/wpdocker.git

sh wpd build
sh wpd start
```

Voilà

## Configurations

At root dir you'll find a ``.env`` file
You can change variables to reflect your setup.

## Usage

Start environment

```sh
sh wpb start (Like docker-compose up -d)
```

Stop environment (Like docker-compose down -v)

```sh
sh wpb stop
```

Print IP (Only on Mac OSX)

```sh
sh wpb ip
```

Attache a bash shell on the wordpress container

```sh
sh wpb bash
```