package(default_visibility = ["//visibility:public"])
cc_library(
  name = 'meta',
  hdrs = glob([
    'include/meta/**/*.hpp',
  ]),
  includes = [
    "include",
  ],
)

cc_library(
  name = 'range-v3',
  hdrs = glob([
    'include/range/v3/**/*.hpp',
  ]),
  deps = [
    ':meta',
  ],
)

