cc_test(
    name = "allocator_test",
    srcs = [
        "allocator_test.cc",
        "//core/utility:allocator",
    ],
    deps = [
        "//core:_ps_optimizer",
        "@brpc//:brpc",
        "@com_google_googletest//:gtest_main",
    ],
    copts = ["-g -ggdb"],
)
