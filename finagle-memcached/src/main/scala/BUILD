scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'finagle-memcached',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/fasterxml/jackson/core:jackson-databind',
    '3rdparty/jvm/com/fasterxml/jackson/module:jackson-module-scala',
    '3rdparty/jvm/com/google/guava',
    '3rdparty/jvm/com/twitter/bijection:core',
    'science/src/java/com/twitter/common/zookeeper:client',
    'science/src/java/com/twitter/common/zookeeper:server-set',
    'science/src/java/com/twitter/common/io:io',
    'science/src/java/com/twitter/common/io:json',
    'science/src/java/com/twitter/common/quantity:quantity',
    '3rdparty/jvm/org/apache/zookeeper:zookeeper-client',
    '3rdparty/jvm/com/google/code/gson',
    '3rdparty/jvm/io/netty',
    'finagle/finagle-netty4',
    'finagle/finagle-serversets',
    'util/util-hashing',
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/io/netty:netty4',
    '3rdparty/jvm/io/netty:netty4-handler-proxy',
    '3rdparty/jvm/io/netty:netty4-http',
    'finagle/finagle-core/src/main/scala:scala',
    'science/src/thrift/com/twitter/thrift:thrift-java',
    'util/util-app/src/main/scala:scala',
    'util/util-collection/src/main/scala:scala',
    'util/util-core/src/main/scala:scala',
    'util/util-logging/src/main/scala:scala',
    'util/util-registry/src/main/scala:scala',
    'util/util-stats/src/main/scala:scala',
  ],
  sources=rglobs('*.scala'),
  resources=['finagle/finagle-memcached/src/main/resources'],
  # Exposes a service-loaded class.
  scope='forced',
)
