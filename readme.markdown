# plex library configs via kometa

i'm trying out using [kometa] to organize my plex libraries. we'll see. using docker to simplify my life:

```bash
docker run --rm -it --env-file docker.env.local -v "$(pwd):/config" kometateam/kometa --run
```