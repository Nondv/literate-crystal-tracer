# WTF is this?

This is based on the ray-tracing example from
[this](https://github.com/mightykho/crystal_tracer) repository.

The idea was to show how we can utilize literate programming for example
projects.

# How to build this

This example is created via Emacs org-mode tangling.

Run `M-x org-babel-tangle` in `source.org` file. This will generate the whole
project in `output/` directory. Later in `output/`:

- `shards install`
- `crystal build --release src/crystal_tracer.cr`
