# tmp

```sh
docker run -it --rm -v "${PWD}:/src" -w /src gcc gcc -o tmp tmp.c
docker run -it --rm -v "${PWD}:/src" -w /src gcc g++ -o tmp tmp.cc
docker run -it --rm -v "${PWD}:/src" -w /src erlang ./tmp.escript
tmp
docker run -it --rm -v "${PWD}:/src" -w /src golang go build tmp.go
docker run -it --rm -v "${PWD}/.stack:/root/.stack" -v "${PWD}:/src" -w /src haskell ./tmp.hs
tmp
docker run -it --rm -v "${PWD}:/src" -w /src denoland/deno run tmp.js
tmp
docker run -it --rm -v "${PWD}:/src" -w /src nickblah/lua lua tmp.lua
tmp
docker run -it --rm -v "${PWD}:/src" -w /src bash ./tmp.sh
tmp
```
