# synchronize in windows

run winscp synchronize as a server


# Usage

1. Clone the proejct into c:/

```shell
git clone https://github.com/chet-cloud/win-service-winscp.git c:/winscp
```

2. Install, start, stop, status, and restart the service

    - open cmd.exe and switch to the directory - c:/winscp

    - input the following commands

```shell
    winscp-service install
    winscp-service start
    winscp-service stop
    winscp-service status
    winscp-service restart
```

or You can open the Services (win+run>services.msc) and operate on winscp service after install the service