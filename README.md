To build the image, run:
```
docker build -t sftp-server .
```

To run the container:
```
docker run -d -p 2022:22 sftp-server
```

To connect using sftp:
```
sftp -oPort=2022 sftp_user@127.0.0.1