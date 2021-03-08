load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Docker

http_archive(
    name = "io_bazel_rules_docker",
    sha256 = "1698624e878b0607052ae6131aa216d45ebb63871ec497f26c67455b34119c80",
    strip_prefix = "rules_docker-0.15.0",
    urls = ["https://github.com/bazelbuild/rules_docker/releases/download/v0.15.0/rules_docker-v0.15.0.tar.gz"],
)

load(
    "@io_bazel_rules_docker//repositories:repositories.bzl",
    container_repositories = "repositories",
)
container_repositories()

load("@io_bazel_rules_docker//repositories:deps.bzl", container_deps = "deps")

container_deps()

# BuildFarm

# BUILDFARM_VERSION = "1.6.0"
# BUILDFARM_EXTERNAL_SHA256 = "e5ebaebead68dc02f386d1577f21ba88a5488349520d895b3740467d1509440f"

# http_archive(
#     name = "bazel_buildfarm",
#     strip_prefix = "bazel-buildfarm-%s" % BUILDFARM_VERSION,
#     sha256 = BUILDFARM_EXTERNAL_SHA256,
#     url = "https://github.com/bazelbuild/bazel-buildfarm/archive/%s.zip" % BUILDFARM_VERSION,
# )

# load("@bazel_buildfarm//:deps.bzl", "buildfarm_dependencies")

# buildfarm_dependencies()

# load("@bazel_buildfarm//:defs.bzl", "buildfarm_init")

# buildfarm_init()



