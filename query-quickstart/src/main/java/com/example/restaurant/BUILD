java_library(
    name = "chef",
    srcs = [
        "Chef.java",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//src/main/java/com/example/dishes:macAndCheese",
        "//src/main/java/com/example/dishes:pizza",
        "//src/main/java/com/example/dishes:smoothie",
    ],
)

java_library(
    name = "cafe",
    srcs = [
        "Cafe.java",
    ],
    visibility = ["//visibility:public"],
    deps = [
        ":chef",
    ],
)
