# tmp

Write temporary code.

## C

```sh
docker run -it --rm -v "${PWD}:/src" -w /src gcc gcc -o tmp tmp.c
./tmp
tmp
```

## C++

```sh
docker run -it --rm -v "${PWD}:/src" -w /src gcc g++ -o tmp tmp.cc
./tmp
tmp
```

## Erlang

```sh
docker run -it --rm -v "${PWD}:/src" -w /src erlang ./tmp.escript
tmp
```

## Golang

```sh
docker run -it --rm -v "${PWD}:/src" -w /src golang go run tmp.go
tmp
```

## Haskell

```sh
docker run -it --rm -v "${PWD}/.stack:/root/.stack" -v "${PWD}:/src" -w /src haskell ./tmp.hs
tmp
```

## Java

```sh
docker run -it --rm -v "${PWD}:/src" -w /src openjdk javac Tmp.java
docker run -it --rm -v "${PWD}:/src" -w /src openjdk java Tmp
tmp
```

## Javascript

```sh
docker run -it --rm -v "${PWD}:/src" -w /src denoland/deno run tmp.js
tmp
```

## Lua

```sh
docker run -it --rm -v "${PWD}:/src" -w /src nickblah/lua lua tmp.lua
tmp
```

## PHP
```sh
docker run -it --rm -v "${PWD}:/src" -w /src php php tmp.php
tmp
```

## Markdown

```sh
docker run -it --rm -v "${PWD}:/docs" -p 3000:3000 dannyben/madness server
```

## Bash

```sh
docker run -it --rm -v "${PWD}:/src" -w /src bash ./tmp.sh
tmp
```

## SQL

```sh
docker run -it --rm -v "${PWD}:/src" -w /src keinos/sqlite3
```

## Mermaid

```sh
docker run -it --rm -u "$(id -u):$(id -g)" -v "${PWD}:/src" -w /src minlag/mermaid-cli -e png -i ./tmp.mmd
```
