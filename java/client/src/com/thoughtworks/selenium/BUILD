java_library(
    name = "selenium",
    exports = [
        ":selenium-lib",
        "//java/client/src/com/thoughtworks/selenium/webdriven",
    ]
)

java_library(
    name = "selenium-lib",
    srcs = glob([ "**/*.java"]),
    deps = [
      "//java/client/src/org/openqa/selenium/remote",
      "//third_party/java/junit",
      "//third_party/java/testng",
    ],
    visibility = [
      "//java/client/src/com/thoughtworks/selenium/webdriven:__pkg__",
    ]
)
