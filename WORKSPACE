load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/znly/rules_go.git",
    commit = "7c43fe7e082e0f627da9cd108863b5c98146da70",
)
load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains", "go_repository")
go_rules_dependencies()
go_register_toolchains(go_version="host")

git_repository(
    name = "build_bazel_rules_apple",
    remote = "https://github.com/znly/rules_apple.git",
    commit = "b2c64f924a2df9108d9b62c82d5650973ee878f1",
)
