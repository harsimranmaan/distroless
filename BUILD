package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_docker//container:container.bzl", "container_bundle")

container_bundle(
    name = "all",
    images = {
        "gcr.io/{PROJECT_ID}/base:latest": "//base:base_debian9",
        "gcr.io/{PROJECT_ID}/base:nonroot": "//base:base-nonroot_debian9",
        "gcr.io/{PROJECT_ID}/base:debug": "//base:debug_debian9",
        "gcr.io/{PROJECT_ID}/base:debug-nonroot": "//base:debug-nonroot_debian9",
        "gcr.io/{PROJECT_ID}/base-debian9:latest": "//base:base_debian9",
        "gcr.io/{PROJECT_ID}/base-debian9:nonroot": "//base:base-nonroot_debian9",
        "gcr.io/{PROJECT_ID}/base-debian9:debug": "//base:debug_debian9",
        "gcr.io/{PROJECT_ID}/base-debian9:debug-nonroot": "//base:debug-nonroot_debian9",
        "gcr.io/{PROJECT_ID}/base-debian10:latest": "//base:base_debian10",
        "gcr.io/{PROJECT_ID}/base-debian10:nonroot": "//base:base-nonroot_debian10",
        "gcr.io/{PROJECT_ID}/base-debian10:debug": "//base:debug_debian10",
        "gcr.io/{PROJECT_ID}/base-debian10:debug-nonroot": "//base:debug-nonroot_debian10",
        "gcr.io/{PROJECT_ID}/static:latest": "//base:static_debian9",
        "gcr.io/{PROJECT_ID}/static:nonroot": "//base:static-nonroot_debian9",
        "gcr.io/{PROJECT_ID}/static-debian9:latest": "//base:static_debian9",
        "gcr.io/{PROJECT_ID}/static-debian9:nonroot": "//base:static-nonroot_debian9",
        "gcr.io/{PROJECT_ID}/static-debian10:latest": "//base:static_debian10",
        "gcr.io/{PROJECT_ID}/static-debian10:nonroot": "//base:static-nonroot_debian10",
        "gcr.io/{PROJECT_ID}/cc:latest": "//cc:cc_debian9",
        "gcr.io/{PROJECT_ID}/cc:debug": "//cc:debug_debian9",
        "gcr.io/{PROJECT_ID}/cc-debian9:latest": "//cc:cc_debian9",
        "gcr.io/{PROJECT_ID}/cc-debian9:debug": "//cc:debug_debian9",
        "gcr.io/{PROJECT_ID}/cc-debian10:latest": "//cc:cc_debian10",
        "gcr.io/{PROJECT_ID}/cc-debian10:debug": "//cc:debug_debian10",
        "gcr.io/{PROJECT_ID}/java:latest": "//java:java8_debian9",
        "gcr.io/{PROJECT_ID}/java:8": "//java:java8_debian9",
        "gcr.io/{PROJECT_ID}/java:debug": "//java:java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java:8-debug": "//java:java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java:11": "//java:java11_debian9",
        "gcr.io/{PROJECT_ID}/java:11-debug": "//java:java11_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9:latest": "//java:java8_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9:8": "//java:java8_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9:debug": "//java:java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9:8-debug": "//java:java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9:11": "//java:java11_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9:11-debug": "//java:java11_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian10:latest": "//java:java11_debian10",
        "gcr.io/{PROJECT_ID}/java-debian10:11": "//java:java11_debian10",
        "gcr.io/{PROJECT_ID}/java-debian10:debug": "//java:java11_debug_debian10",
        "gcr.io/{PROJECT_ID}/java-debian10:11-debug": "//java:java11_debug_debian10",
        "gcr.io/{PROJECT_ID}/java/jetty:latest": "//java/jetty:jetty_java8_debian9",
        "gcr.io/{PROJECT_ID}/java/jetty:java8": "//java/jetty:jetty_java8_debian9",
        "gcr.io/{PROJECT_ID}/java/jetty:debug": "//java/jetty:jetty_java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java/jetty:java8-debug": "//java/jetty:jetty_java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java/jetty:java11": "//java/jetty:jetty_java11_debian9",
        "gcr.io/{PROJECT_ID}/java/jetty:java11-debug": "//java/jetty:jetty_java11_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9/jetty:latest": "//java/jetty:jetty_java8_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9/jetty:java8": "//java/jetty:jetty_java8_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9/jetty:debug": "//java/jetty:jetty_java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9/jetty:java8-debug": "//java/jetty:jetty_java8_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9/jetty:java11": "//java/jetty:jetty_java11_debian9",
        "gcr.io/{PROJECT_ID}/java-debian9/jetty:java11-debug": "//java/jetty:jetty_java11_debug_debian9",
        "gcr.io/{PROJECT_ID}/java-debian10/jetty:latest": "//java/jetty:jetty_java11_debian10",
        "gcr.io/{PROJECT_ID}/java-debian10/jetty:java11": "//java/jetty:jetty_java11_debian10",
        "gcr.io/{PROJECT_ID}/java-debian10/jetty:debug": "//java/jetty:jetty_java11_debug_debian10",
        "gcr.io/{PROJECT_ID}/java-debian10/jetty:java11-debug": "//java/jetty:jetty_java11_debug_debian10",
        "gcr.io/{PROJECT_ID}/python3:latest": "//experimental/python3:python3",
        "gcr.io/{PROJECT_ID}/python3:debug": "//experimental/python3:debug",
        "gcr.io/{PROJECT_ID}/python3:nonroot": "//experimental/python3:python3-nonroot",
        "gcr.io/{PROJECT_ID}/python3:debug-nonroot": "//experimental/python3:debug-nonroot",
        "gcr.io/{PROJECT_ID}/python2.7:latest": "//experimental/python2.7:python27",
        "gcr.io/{PROJECT_ID}/python2.7:debug": "//experimental/python2.7:debug",
        "gcr.io/{PROJECT_ID}/nodejs:latest": "//experimental/nodejs",
        "gcr.io/{PROJECT_ID}/nodejs:debug": "//experimental/nodejs:debug",
        "gcr.io/{PROJECT_ID}/dotnet:latest": "//experimental/dotnet:dotnet_debian9",
        "gcr.io/{PROJECT_ID}/dotnet:debug": "//experimental/dotnet:debug_debian9",
        "gcr.io/{PROJECT_ID}/dotnet-debian9:latest": "//experimental/dotnet:dotnet_debian9",
        "gcr.io/{PROJECT_ID}/dotnet-debian9:debug": "//experimental/dotnet:debug_debian9",
        "gcr.io/{PROJECT_ID}/dotnet-debian10:latest": "//experimental/dotnet:dotnet_debian10",
        "gcr.io/{PROJECT_ID}/dotnet-debian10:debug": "//experimental/dotnet:debug_debian10",
    },
)

load("@io_bazel_rules_docker//contrib:push-all.bzl", "container_push")

container_push(
    name = "publish",
    bundle = ":all",
    format = "Docker",
)
