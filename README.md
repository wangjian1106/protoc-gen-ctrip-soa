# Ctrip SOA Protoc Plugin

An plugin that alters code generated by the default protoc implementation.

This plugin generate ctrip soa service inteface and client stub.

Build instructions

1.) Install Bazel http://www.bazel.io/docs/install.html. We use this build tool because that's what google/protobufs uses. Bazel requires Java.

2.) Build with `bash build_all.sh`