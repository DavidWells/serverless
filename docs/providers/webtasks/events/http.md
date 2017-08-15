<!--
title: Serverless Framework - Webtask Events - API Gateway
menuText: API Gateway
menuOrder: 1
description: Setting up http events with Webtask via the Serverless Framework
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/webtasks/events/apigateway)
<!-- DOCS-SITE-LINK:END -->

# Http Event

Trigger your webtask function via the `http` event

```yml
functions:
  hello:
    handler: handlerFile
```

By default webtasks functions are triggered by http.

Also note, you do not need to specify the `method` like other serverless providers
