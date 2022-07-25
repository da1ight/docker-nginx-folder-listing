# Dockerfile with nginx folder listing enabled

The nginx powered image to get a file directory listing.

Map a desired directory to `/mnt/data` container mountpoint.

Example:
```
docker run -p 80:80 -v /mnt/smth/logs:/mnt/data da1ight/nginx-folder-listing:latest
```
