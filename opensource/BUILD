load("@rules_android//android:rules.bzl", "android_library")

# aliases that creates bazel targets that are equivalent to blaze

java_import(
    name = "androidsdk_compiletime",
    jars = [
        "@androidsdk//:platforms/android-35/android.jar",
    ],
    neverlink = 1,
    visibility = [
        "//visibility:public",
    ],
)

java_import(
    name = "entry_point_import",
    jars = [
        "entry_point_deploy.jar",
    ],
    neverlink = 1,
    visibility = [
        "//visibility:public",
    ],
)
