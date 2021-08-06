# config_agent

Inspired by the [dbus-api](https://github.com/LadySerena/dbus-api) I wrote I wanted to expand it to handle the following
things that I consider to be essential to manage a system: restarts, service management, package management, updating
configuration files, adding users, managing ssh keys, and other use cases as they come up.

## Dev Notes to be cleaned up

using tonic as the grpc server

will need something to generate code from the .proto file

will need to port dbus stuff into rust from go for the service management

## References

- [tonic docs.rs](https://docs.rs/tonic/0.5.0/tonic/)
- [tonic github](https://github.com/hyperium/tonic)
- [protobuf spec](https://developers.google.com/protocol-buffers/)