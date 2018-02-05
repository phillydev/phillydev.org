# phillydev.org

This repository contains the Jekyll project that is used to build [phillydev.org](http://phillydev.org/).

## Local Development

In order to develop against the site locally, you'll need to install:

- Ruby
- Bundler

Once those are installed, install the Ruby specific dependencies:

```bash
$ bundle
```

After that, you should be able to use `jekyll serve` to view changes [locally](http://localhost:9000/) as you make them.

## Deployment

Deployment is handled automatically by Netlify on merges to `master`.
