# papinlahteenmatruusi

www.papinlahteenmatruusi.fi

## Build

### Windows
```bash
docker run --rm --volume=$(pwd -W):/srv/jekyll \
-it jekyll/jekyll:latest \
jekyll build
```

You must use Git Bash.

### macOS/Linux
```bash
## Coming soon, nearly same as on Windows, but without `-W` in `pwd`!
```

## Devserver
### Windows
```bash
docker run -p 4000:4000 -v $(pwd -W):/site bretfisher/jekyll-serve
```

### macOS/Linux
```bash
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

