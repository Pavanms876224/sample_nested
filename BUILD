load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "sample_lib",
    srcs = ["libsample_library.a"],
    hdrs = glob(["include/**/*.h"]),
    includes = ["include", "include/ara"],
    visibility = ["//visibility:public"],
)
