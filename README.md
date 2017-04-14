# q3a-server

Copy pak0.pk3 from Quake 3 Arena CDROM/Data to the project root

## Build

```
docker build -t q3a-server .
```

## Run

```
docker run -it -p 27960:27960/udp q3a-server server
```
