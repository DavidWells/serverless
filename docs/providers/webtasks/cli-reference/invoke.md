<!--
title: Serverless Framework Commands - Webtasks - Invoke
menuText: invoke
menuOrder: 8
description: Invoke an Webtask Function using the Serverless Framework
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/webtasks/cli-reference/invoke)
<!-- DOCS-SITE-LINK:END -->

# Webtasks - Invoke

Invokes deployed function. It allows to send event data to the function, read logs and display other important information of the function invocation.

```bash
serverless invoke [local] --function functionName
```

## Options
- `--function` or `-f` The name of the function in your service that you want to invoke. **Required**.
- `--stage` or `-s` The stage in your service you want to invoke your function in.
- `--region` or `-r` The region in your stage that you want to invoke your function in.
- `--data` or `-d` String data to be passed as an event to your function. By default data is read from standard input.
- `--path` or `-p` The path to a json file with input data to be passed to the invoked function. This path is relative to the root directory of the service.
- `--type` or `-t` The type of invocation. Either `RequestResponse`, `Event` or `DryRun`. Default is `RequestResponse`.
- `--log` or `-l` If set to `true` and invocation type is `RequestResponse`, it will output logging data of the invocation. Default is `false`.

## Provided lifecycle events
- `invoke:invoke`
