# asf-backup


https://justarchinet.github.io/ASF-WebConfigGenerator

https://github.com/JustArchiNET/ArchiSteamFarm/releases/

```
rpm -Uvh https://packages.microsoft.com/config/centos/8/packages-microsoft-prod.rpm
yum install dotnet-runtime-5.0

yum install epel-release
yum install screen -y

screen -S asf
./ArchiSteamFarm
screen -ls
screen -U -r asf
kill -9 pid

```
```

{
  "SteamLogin": "?????",
  "SteamPassword": "???????",
  "Enabled": true
}

```
