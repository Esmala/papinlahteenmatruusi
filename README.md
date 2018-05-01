# papinlahteenmatruusi

www.papinlahteenmatruusi.fi

## Build (on Windows)
```bash
docker run --rm --volume=$(pwd -W):/srv/jekyll \
-it jekyll/jekyll:latest \
jekyll build
```

You must use Git Bash.

## Build (on macOS/Linux)
```bash
## Coming soon, nearly same as on Windows, but without `-W` in `pwd`!
```