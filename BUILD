package(default_visibility = ["//visibility:public"])
# load("@io_bazel_rules_docker//container:container.bzl", "container_image")

filegroup(
    name = "example_configs",
    srcs = glob(["*.example"]),
)

cc_binary(
    name = "main",
    srcs = ["main.cc"],
)

sh_binary(
    name = "runner",
    srcs = ["runner.sh"]
)

# container_image(
#     name = "build-server",
#     # deps
#     base = "@bazel_buildfarm//java_image_base",
#     # files = ["//java/com/example/app:Hello_deploy.jar"],
#     cmd = ["echo", "hello!"]
# )