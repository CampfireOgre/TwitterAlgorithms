scala_library(
    sources = [
        "*.scala",
    ],
    compiler_option_sets = ["fatal_warnings"],
    tags = [
        "bazel-compatible",
        "bazel-only",
    ],
    dependencies = [
        "kafka/finagle-kafka/finatra-kafka/src/main/scala",
        "src/thrift/com/twitter/ads/billing/spendserver:spendserver_thrift-scala",
        "src/thrift/com/twitter/ads/eventstream:eventstream-scala",
        "unified_user_actions/adapter/src/main/scala/com/twitter/unified_user_actions/adapter:base",
        "unified_user_actions/adapter/src/main/scala/com/twitter/unified_user_actions/adapter/common",
        "unified_user_actions/thrift/src/main/thrift/com/twitter/unified_user_actions:unified_user_actions-scala",
    ],
)
