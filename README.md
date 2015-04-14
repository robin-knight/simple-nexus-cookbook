# Description

This cookbook installs only nexus and provides few typical configurations.
It doesn't install or depends on java, apache, nginx, etc...

## Usage

Default recipe only creates user/group and arks nexus.
You are free to do anything with installation.

It better to you to wrap this cookbook in yours' company cookbook.


# Examples

You can visit fixture cookbook [test-nexus](test/fixtures/cookbooks/test-nexus)

# Requirements

## Platform:

* Debian
* Ubuntu
* Centos

## Cookbooks:

* ark

# Attributes

*No attributes defined*

# Recipes

* simple-nexus::default

# License and Maintainer

Maintainer:: Yauhen Artsiukhou (<jsirex@gmail.com>)

License:: Apache
