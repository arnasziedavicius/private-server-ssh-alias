# private-server-ssh-alias

## Setup

Replace example values in `config` and paste the contents in your local SSH configuration file. Local config file can be found in `.ssh` folder in your system user's directory. Make sure to place the pem keys within the same folder as well.

## Usage

Connect to bastion server:
``` bash
ssh server-bastion
```

Connect to private server:
``` bash
ssh server-private
```
