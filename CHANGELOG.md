### 1.1.6

- upgrade @mapbox/dyno and @mapbox/dynamodb-test

### 1.1.4

- fix a bug in `.status()` when using promises

### 1.1.3

- more permissive engines.node

### 1.1.2

- fix a bug where the CLI tool would exit 0 even if the process failed

### 1.1.1

- fix a bug in `.status()` that failed part checks on finished jobs

### 1.1.0

- switch to namespaced package `@mapbox/watchbot-progress`
- adds `.reduceSent()` for flagging a job as having had reduce steps taken
- adds optional `part` argument to `.status()`, allowing you to learn if a single part has been completed or not

### 1.0.0

- Migrates progress functions, tests, and related documentation from watchbot
- Exposes DynamoDB creation and progress tooling functions
