package(default_visibility = ["//visibility:public"])

cc_library(
    name = "meta",
    hdrs = glob([
        "include/meta/**/*.hpp",
    ]),
    includes = [
        "include",
    ],
#    strip_include_prefix = "include",
)

cc_library(
    name = "range-v3",
    hdrs = glob([
        "include/range/v3/**/*.hpp",
    ]),
#    strip_include_prefix = "include",
    deps = [
        ":meta",
    ],
)
