# Windows Servercore PowerShell execution script. This sample uses a base image compatible with Windows 10
FROM mcr.microsoft.com/windows/servercore:10.0.14393.6709

WORKDIR /scripts

COPY HelloWorld.ps1 .

CMD [ "PowerShell", "-c", "/scripts/HelloWorld.ps1" ]