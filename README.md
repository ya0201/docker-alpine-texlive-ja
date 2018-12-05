# ya0201/alpine-texlive-ja

Forked from [Paperist/docker-alpine-texlive-ja] \(under the MIT License\).

[Paperist/docker-alpine-texlive-ja]: https://github.com/Paperist/docker-alpine-texlive-ja

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [License](#license)

## Install

```bash
docker pull ya0201/alpine-texlive-ja
```

## Usage

```bash
$ docker run --rm -it -v $PWD:/workdir ya0201/alpine-texlive-ja
$ latexmk -C main.tex && latexmk main.tex && latexmk -c main.tex
```

## License

MIT © ya0201
