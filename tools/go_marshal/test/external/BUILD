package(licenses = ["notice"])

load("//tools/go_marshal:defs.bzl", "go_library")

go_library(
    name = "external",
    testonly = 1,
    srcs = ["external.go"],
    importpath = "gvisor.dev/gvisor/tools/go_marshal/test/external",
    visibility = ["//tools/go_marshal/test:gomarshal_test"],
)
