# docker-installer

An extremely simple Docker installer for Ubuntu and, probably, Debian. Based on the official Docker documentation.

## Usage

You do not need to clone this repository. Instead, confirm that `curl` is installed, then paste the command below to run the script.

```sh
bash <(curl -s https://raw.githubusercontent.com/yeenbean/docker-installer/main/install.sh)
```

**Note:** This script will not add your user to the docker group as I do not want to assume the currently logged-in user should have access to that group. Therefore, you will need to add your desired user to the docker group manually with `usermod -a -G docker <username>`.
