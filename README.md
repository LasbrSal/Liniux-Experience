# Liniux Experience - DIO Bootcamp

## Directory and user creation script

This is a bash script for creating directories, user groups, and users, as well as specifying permissions on directories.

## Description

`iac1.sh` is an automation script that simplifies the creation of directories, user groups, and users on Unix/Linux systems. It also specifies the appropriate permissions on the corresponding directories, making it easier to organize and manage system resources.

## Features

- Creation of specific directories, including:
  - /publico
  - /adm
  - /ven
  - /sec

- Creation of custom user groups:
  - GRP_ADM
  - GRP_VEN
  - GRP_SEC

- Creation of users in corresponding groups with encrypted passwords:
  - GRP_ADM:
    - user01
    - user02
    - user03

  - GRP_VEN:
    - user04
    - user05
    - user06

  - GRP_SEC:
    - user07
    - user08
    - user09

- Specification of directory permissions:
  - /adm: Full access for the GRP_ADM group (770).
  - /ven: Full access for the GRP_VEN group (770).
  - /sec: Full access for the GRP_SEC group (770).
  - /publico: Permissions not specified.

## Prerequisites

Before using the script, make sure your system has the `openssl` utility installed.

## How to Use

1. Clone this repository to your machine:

   ```shell
   git clone git@github.com:lasbrDev/linux-projeto1-iac.git

2. Execute the script:

    ```shell
    ./iac1.sh

The script will create directories, user groups, and users, and specify permissions on the corresponding directories.

## Contributing

Feel free to contribute improvements, fixes, or suggestions to this project. Just create a pull request, and we'll be happy to review your contributions.

## License

This project is distributed under the **MIT License**.

