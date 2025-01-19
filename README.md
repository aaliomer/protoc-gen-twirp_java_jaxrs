Twirp generator for Java/Jakarta-RS Client
======================================

This is a protobuf generator that creates a Java/Jakarta-RS client for
[Twirp](https://github.com/twitchtv/twirp).

This is a fork of https://github.com/fajran/protoc-gen-twirp_java_jaxrs

Build
-----

    go get github.com/aaliomer/protoc-gen-twirp_java_jakarta


Usage
-----

    export PATH=$PATH:$GOPATH/bin
    protoc service.proto --java_out=src/main/java --twirp_java_jakarta_out=src/main/java

