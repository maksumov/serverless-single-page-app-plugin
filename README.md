# serverless-single-page-app-plugin

A plugin to simplify deploying Single Page Application using S3 and CloudFront

## Installation

1. `npm config set @maksumov:registry https://npm.pkg.github.com/maksumov`
2. `npm install @maksumov/serverless-single-page-app-plugin`

## Usage

This is plugin for [serverless](https://www.npmjs.com/package/serverless). Just install plugin and add plugin to `serverless.yml`:

```yaml
plugins:
  - serverless-finch
  - @maksumov/serverless-single-page-app-plugin
```

Sources:

1. [https://github.com/serverless/examples/tree/master/aws-node-single-page-app-via-cloudfront](https://github.com/serverless/examples/tree/master/aws-node-single-page-app-via-cloudfront)
2. [https://github.com/boale/serverlessTestApp](https://github.com/boale/serverlessTestApp)
