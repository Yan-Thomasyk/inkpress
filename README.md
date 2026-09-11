# inkpress

Static blog generator: markdown in, tidy HTML out

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Features

- Single template, plain str.format, no Jinja
- RSS feed generation
- Markdown posts with fenced code and tables
- Index page with post list by date

## Installation

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
