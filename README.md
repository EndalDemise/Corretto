# Corretto

Install Amazon Corretto 8 on Windows

Usage
playbook.yml:

- { role: ansible-windows-java }

requirements.yml:

- src: https://github.com/EndalDemise/Corretto.git

version: master

name: Corretto

Options

Override these variables to change the version of JDK installed.


jdk_package: jdk8

java_major_version: 1.8.0

java_minor_version: 222




This role installs JDK.
