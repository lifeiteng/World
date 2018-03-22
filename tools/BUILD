package(default_visibility = ["//visibility:public"])

cc_library(
    name = "audioio",
    srcs = ["audioio.cpp"],
    hdrs = [
      "audioio.h",
    ],
    copts = ["-Itools"],
)

cc_library(
    name = "parameterio",
    srcs = ["parameterio.cpp"],
    hdrs = [
      "parameterio.h",
    ],
    copts = ["-Itools"],
)

cc_library(
    name = "libtools",
    srcs = [
      "audioio.cpp",
      "parameterio.cpp",
    ],
    hdrs = [
      "audioio.h",
      "parameterio.h",
    ],
    copts = ["-Itools"],
)
