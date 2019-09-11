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


openjdk version "1.8.0_222"
OpenJDK Runtime Environment Corretto-8.222.10.3 (build 1.8.0_222-b10)
OpenJDK 64-Bit Server VM Corretto-8.222.10.3 (build 25.222-b10, mixed mode)


This role installs JDK.
