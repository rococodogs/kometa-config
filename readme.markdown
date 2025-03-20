# plex library configs via kometa

trying out [kometa] to organize my plex libraries. we'll see. using docker to simplify my life:

```bash
docker run --rm -it --env-file docker.env.local -v "$(pwd):/config" kometateam/kometa --run
```

[kometa]: https://kometa.wiki/
