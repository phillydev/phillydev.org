# phillydev.org

This repository contains the Jekyll project that is used to build [phillydev.org](http://phillydev.org/).

## Local Development

In order to develop against the site locally, you'll need to install:

- Ruby & Bundler
- Node.js & NPM

Once everything is installed, install the Ruby and Node.js specific dependencies:

```bash
$ npm install grunt-cli
$ npm install
$ bundle install
```

After that, you should be able to use `grunt serve` to view changes [locally](http://localhost:9000/) as you make them.

## Deployment

Deployment is handled automatically by [Travis CI](https://travis-ci.org/phillydev/phillydev.org) on merges to `master`. The deployment process writes to an [Amazon S3](http://aws.amazon.com/s3/) bucket that is configured to serve static website content. The DNS for that bucket is handled by [Route 53](http://aws.amazon.com/route53/).

Check [.travis.yml](.travis.yml) for more detail.
