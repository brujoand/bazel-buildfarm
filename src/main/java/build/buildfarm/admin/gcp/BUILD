java_library(
    name = "gcp",
    srcs = glob(["*.java"]),
    visibility = ["//visibility:public"],
    deps = [
        "//src/main/java/build/buildfarm/admin",
        "//src/main/protobuf:build_buildfarm_v1test_buildfarm_java_proto",
        "@googleapis//:google_rpc_code_java_proto",
        "@googleapis//:google_rpc_error_details_java_proto",
        "@googleapis//:google_rpc_status_java_proto",
        "@maven//:com_google_guava_guava",
        "@maven//:com_google_protobuf_protobuf_java_util",
        "@maven//:org_springframework_spring_beans",
        "@maven//:org_springframework_spring_context",
        "@maven//:org_springframework_spring_core",
        "@remote_apis//:build_bazel_remote_execution_v2_remote_execution_java_proto",
    ],
)
