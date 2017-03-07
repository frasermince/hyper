<div align="center">
<h1>
<img src="docs-src/src/_static/hyper@2x.png"
      alt="Hyper"
      width="300">
</h1>
</div>

<p align="center">
<em>Type-safe, statically checked composition of HTTP servers</em>
</p>

<p align="center">
<a href="http://hyper.wickstrom.tech/tutorials/getting-started-with-hyper.html">Getting Started</a>
| <a href="http://hyper.wickstrom.tech">Documentation</a> (also in <a href="https://owickstrom.github.io/hyper/hyper.pdf">PDF</a>)
| <a href="http://hyper.wickstrom.tech/faq.html">FAQ</a>
| <a href="examples/">Examples</a>
</p>

<hr>

Hyper is an experimental middleware architecture for HTTP servers written in PureScript. Its main focus is correctness and type-safety, using type-level information to enforce correct composition and abstraction for web servers. The Hyper project is also a breeding ground for higher-level web server constructs, which tend to fall under the “framework” category.

To learn
more about Hyper, check out the [documentation](http://hyper.wickstrom.tech)
and [the Getting Started
tutorial](http://hyper.wickstrom.tech/tutorials/getting-started-with-hyper.html).

<p align="right">
<a href="https://travis-ci.org/owickstrom/hyper"><img alt="Build Status" src="https://travis-ci.org/owickstrom/hyper.svg?branch=master" /></a>
<a href="https://github.com/owickstrom/hyper/releases"><img alt="Latest release" src="http://img.shields.io/github/release/owickstrom/hyper.svg" /></a>

</p>

<hr>

## Build

Install dependencies and build:

```bash
bower install
pulp build
```

### Running Tests

```bash
pulp test
```

### Running Examples

```bash
# for examples using the node server:
npm install
pulp run -I examples --main Examples.<example-name>
# for instance to run HelloHyper:
pulp run -I examples --main Examples.HelloHyper
```

### Building all Examples

```bash
npm install # for examples using the node server
make examples
```

### Building Documentation

See [docs-src/README.md](docs-src/README.md) for prerequisites, setup, and
how to work with the documentation.

Then, for the release build, run:

```bash
make docs
```

## CodeScene Status

[![](https://codescene.io/projects/49/status.svg) Get more details at **codescene.io**.](https://codescene.io/projects/49/jobs/latest-successful/results)

## License

[Mozilla Public License Version 2.0](LICENSE)
