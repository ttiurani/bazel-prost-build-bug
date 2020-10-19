package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_rust//rust:rust.bzl", "rust_library")

rust_library(
    name = "demo",
    deps = [
        "//third_party/cargo:demo_prost_build",
    ],
    srcs = glob(["src/**"]),
)
