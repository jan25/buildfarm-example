# buildfarm-example

Example project to use bazel buildfarm for remote execution and caching.

bru can be used to view builds with build events either from clients(or buildfarm server?)

## Went well



## Didn't go well

```bash
# This didn't work
bazel run  @bazel_buildfarm//src/main/java/build/buildfarm:buildfarm-server $(pwd)/server.config.example
```