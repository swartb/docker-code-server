# code-server-custom

Fork of https://github.com/linuxserver/docker-code-server

2022.02.23
  - changed portnumber for the webinterface
  - implemented changes from this PR to support SSL: https://github.com/linuxserver/docker-code-server/pull/23/commits/351c779a5c9457c45760fc0d74157e406d632a5f
    (untested at this moment)
    
    
## Environment variables:
|Name|Description|
|-|-|
|PASSWORD|password|
|SERVER_PORT|listening port|
|SSL_ENABLED|boolean|
|PUID|1000|
|PGID|1000|
