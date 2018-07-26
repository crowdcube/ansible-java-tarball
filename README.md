# Ansible Role: Java

Installs OpenJDK 10 via the tarball

## Requirements

Ansible 2.5+

## Role Variables

Available variables are listed below, along with default values:

    java_home: ""

If set, the role will set the global environment variable `JAVA_HOME` to this value.

    openjdk_url: https://download.java.net/java/GA/jdk10/10.0.2/19aef61b38124481863b1413dce1855f/13/openjdk-10.0.2_linux-x64_bin.tar.gz
    
The source tarball from which to install OpenJDK

    openjdk_checksum: sha256:f3b26abc9990a0b8929781310e14a339a7542adfd6596afb842fa0dd7e3848b2

Checksum of the tarball


## Dependencies

None.
