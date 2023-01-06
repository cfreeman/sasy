# SASY ★ Sachsian Syndicate

## Setup a local development environment for the website.
```bash
docker run -v $PWD:/home/data -p 1313:1313 -p 1612:1612 -it cfreeman/hugo /bin/bash
cd /home/data
hugo server --buildFuture --bind 0.0.0.0 -D
```

## TODO
* Build a tool to help automate the archival process.
* robots.txt, rss, and sitemap.xml config.

