<!--
title: Serverless Framework Commands - Webtasks - Remove
menuText: remove
menuOrder: 15
description: Remove a deployed Service and all of its Webtask Functions, Events and Resources
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/webtasks/cli-reference/remove)
<!-- DOCS-SITE-LINK:END -->

# Webtasks - Remove

The `sls remove` command will remove the deployed service, defined in your current working directory,  from the provider.

```bash
serverless remove
```

## Options
- `--stage` or `-s` The name of the stage in service.
- `--region` or `-r` The name of the region in stage.
- `--verbose` or `-v` Shows all stack events during deployment.

## Provided lifecycle events
- `remove:remove`
