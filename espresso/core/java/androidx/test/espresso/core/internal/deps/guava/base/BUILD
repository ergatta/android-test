# Description:
#    Redefinition of repackaged guava classes that were mistakenly exposed in public EspressoOptional API

load("@rules_android//android:rules.bzl", "android_library")

licenses(["notice"])

package(
    default_applicable_licenses = ["//:license"],
    default_visibility = ["//espresso/core/java/androidx/test/espresso:espresso_pkg"],
)

android_library(
    name = "base",
    srcs = glob(["*java"]),
    deps = [
        "//opensource/androidx:annotation",
        "//runner/monitor",
    ],
)
