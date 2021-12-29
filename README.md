# FactorioServer
## Update Factorio Server

- Log into server
- Go to opt folder

`cd /opt`
- Get latest Factorio build

`wget -O factorio_headless_tar.gz https://factorio.com/get-download/stable/headless/linux64`

- Stop the Factorio Service

`service factorio stop`

- Unpack the Factorio TAR

`sudo tar -xf factorio_headless_tar.gz`

- Restart the Factorio Service

`service factorio start`
