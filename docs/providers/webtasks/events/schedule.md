<!--
title: Serverless Framework - Webtask Events - Scheduled & Recurring
menuText: Schedule
menuOrder: 4
description: Setting up Scheduled, Recurring, CRON Task Events with Webtask via the Serverless Framework
layout: Doc
-->

<!-- DOCS-SITE-LINK:START automatically generated  -->
### [Read this on the main serverless docs site](https://www.serverless.com/framework/docs/providers/webtasks/events/schedule)
<!-- DOCS-SITE-LINK:END -->

# Schedule

The following config will attach a schedule event and causes the function `crawl` to be called every 2 hours. The configuration allows you to attach multiple schedules to the same function.

You can either use the `rate` or `cron` syntax.

```yml
functions:
  crawl:
    handler: crawl
    events:
      - schedule: rate(2 hours)
```

or with default cron syntax

```yml
functions:
  crawl:
    handler: crawl
    events:
      - schedule: cron(0 12 * * ? *)
```
