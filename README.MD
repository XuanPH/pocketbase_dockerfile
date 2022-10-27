# Dockerfile for [Pocketbase](https://pocketbase.io/)

## Run the following command to build the image:

```
docker build -t pocketbase .
```

## Run

### Docker cli

```sh
docker run --name pocketbase  -t -d -p 8090:8090 -v /path/to/backup_db:/usr/local/bin/pb_data pocketbase
```

## Related Repositories

- [PocketBase](https://github.com/pocketbase/pocketbase)


## Noted: SCP Copy file
scp /path/to/folder/db/* username@ip:/path/to/db/on/server
