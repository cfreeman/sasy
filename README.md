# SASY ★ Sachsian Syndicate

## Setup a local development environment for the website.
```bash
docker run -v $PWD:/home/data -p 1313:1313 -p 1612:1612 -it cfreeman/hugo /bin/bash
cd /home/data
hugo server --buildFuture --bind 0.0.0.0 -D
```

## Rebuilding and uploading the website.
```bash
hugo
cd public
git add --all
git commit -m "Publish to gh-pages"
cd ..
git push origin gh-pages
```

## TODO
* CSS blend mode for images
* ~~Create favicon~~
* Setup server config
