<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table Of Content

- [Valid Rate](#valid-rate)
- [CRON](#cron)
- [Install](#install)
- [Import](#import)
- [Execute](#execute)
- [Deploy](#deploy)
- [Logging](#logging)
- [Remove](#remove)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


### Valid Rate
- `minute`
- `minutes` 
- `hour` 
- `hours`
- `day` 
- `days`
- [Schedule Rate Syntax](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/ScheduledEvents.html)

### CRON 
- [Generator](https://www.freeformatter.com/cron-expression-generator-quartz.html)

### Install
```sh
yarn add --dev serverless-offline-scheduler
```

### Import
```yml
plugins:
  - serverless-offline-scheduler
```

### Execute
```sh
sls schedule
```

### Deploy
```sh
sls deploy
```

### Logging
```sh
sls log -f hello -s dev -t
```

### Remove
```sh
sls remove
```

