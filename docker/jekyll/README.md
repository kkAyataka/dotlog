# Jekyll


**Run**:

```console
docker run --rm -v ./:/work -p 4000:4000 -p 35729:35729 dotlog
```

**Build**:

```console
docker build -f docker/jekyll/Dockerfile . -t dotlog
```
