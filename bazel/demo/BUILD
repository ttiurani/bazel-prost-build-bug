package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_rust//rust:rust.bzl", "rust_library", "rust_test")
load("//:format.bzl", "rust_format")

rust_library(
    name = "demo-bazel-rust-lib",
    deps = [
        "//third_party/cargo:demo-prost-build",
    ],
    srcs = glob(["src/**"]),
)
