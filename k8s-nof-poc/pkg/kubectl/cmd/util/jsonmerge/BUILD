package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["jsonmerge.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/util/strategicpatch:go_default_library",
        "//pkg/util/yaml:go_default_library",
        "//vendor:github.com/evanphx/json-patch",
        "//vendor:github.com/golang/glog",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
)
