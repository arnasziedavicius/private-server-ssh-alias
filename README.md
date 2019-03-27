# private-server-ssh-alias

## Setup

Copy and paste [config](config) contents in your local SSH configuration file and replace example values with your server information.

Local config file can be found in `.ssh` folder in your system user's directory. Make sure to place the pem keys within the same folder as well.

## Usage

Connect to bastion server:
``` bash
ssh server-bastion
```

Connect to private server:
``` bash
ssh server-private
```
