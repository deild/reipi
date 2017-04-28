# Serve content
To serve content, execute the following command inside the reipi directory.
```
$ hugo server
```
# Generate website
To generate Hugo website source type the following command.
```
$ hugo --theme=reipi
```
# Deploy reipi on GitHub pages
Anytime, you can regenerate your site with:
```
$ (cd ..; hugo --theme=reipi)
$ git add --all
$ git commit -m "<some change message>"
$ git push -f origin gh-pages
```
