# Tempest protobufs

[![Go Reference](https://pkg.go.dev/badge/github.com/tempestdx/protobuf)](https://pkg.go.dev/github.com/tempestdx/protobuf)

The official [Tempest][tempest] Protocol Buffer definitions repository. This
repository contains the protocol buffer definitions used by Tempest Private Apps
and their corresponding Go-generated code.

## Overview

This repository contains Protocol Buffer (protobuf) definitions that define the
core APIs and data structures used by Tempest Private Apps. These definitions
serve as the contract between Tempest and Private Apps, enabling seamless
integration and communication.

## Package index

- [`tempestdx/app/v1`](https://pkg.go.dev/github.com/tempestdx/protobuf/gen/go/tempestdx/app/v1)
  Core protocol definitions for Tempest Private Apps
- [`tempestdx/app/v1/appv1connect`](https://pkg.go.dev/github.com/tempestdx/protobuf/gen/go/tempestdx/app/v1/appv1connect)
  Connect-based RPC service definitions for Tempest Private Apps

## Support

To share any requests, bugs or comments, please [open an issue][issues] or
[submit a pull request][pulls].

[goref]: https://pkg.go.dev/github.com/tempestdx/protobuf
[issues]: https://github.com/tempestdx/protobuf/issues/new
[pulls]: https://github.com/tempestdx/protobuf/pulls
[tempest]: https://tempestdx.com/
