package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["fake.go"],
    tags = ["automanaged"],
    deps = [
        "//federation/client/clientset_generated/federation_internalclientset:go_default_library",
        "//pkg/api:go_default_library",
        "//pkg/api/meta:go_default_library",
        "//pkg/api/testapi:go_default_library",
        "//pkg/api/validation:go_default_library",
        "//pkg/apimachinery/registered:go_default_library",
        "//pkg/apis/meta/v1:go_default_library",
        "//pkg/client/clientset_generated/internalclientset:go_default_library",
        "//pkg/client/restclient:go_default_library",
        "//pkg/client/restclient/fake:go_default_library",
        "//pkg/client/typed/discovery:go_default_library",
        "//pkg/kubectl:go_default_library",
        "//pkg/kubectl/cmd/util:go_default_library",
        "//pkg/kubectl/resource:go_default_library",
        "//pkg/runtime:go_default_library",
        "//pkg/runtime/schema:go_default_library",
        "//pkg/runtime/serializer:go_default_library",
        "//vendor:github.com/emicklei/go-restful/swagger",
        "//vendor:github.com/spf13/cobra",
        "//vendor:github.com/spf13/pflag",
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
