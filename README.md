[//]: # (This file was autogenerated using `zio-sbt-website` plugin via `sbt generateReadme` command.)
[//]: # (So please do not edit it manually. Instead, change "docs/index.md" file or sbt setting keys)
[//]: # (e.g. "readmeDocumentation" and "readmeSupport".)

# ZIO Connect

ZIO connectors are Sources, Sinks and Pipelines for channeling data. They are easy to use, and they are designed to be
composable. You can use them to build pipelines that can be used to process data.

[![Production Ready](https://img.shields.io/badge/Project%20Stage-Production%20Ready-brightgreen.svg)](https://github.com/zio/zio/wiki/Project-Stages) ![CI Badge](https://github.com/zio/zio-connect/workflows/CI/badge.svg) [![Sonatype Releases](https://img.shields.io/nexus/r/https/oss.sonatype.org/dev.zio/zio-connect-file_2.13.svg?label=Sonatype%20Release)](https://oss.sonatype.org/content/repositories/releases/dev/zio/zio-connect-file_2.13/) [![Sonatype Snapshots](https://img.shields.io/nexus/s/https/oss.sonatype.org/dev.zio/zio-connect-file_2.13.svg?label=Sonatype%20Snapshot)](https://oss.sonatype.org/content/repositories/snapshots/dev/zio/zio-connect-file_2.13/) [![javadoc](https://javadoc.io/badge2/dev.zio/zio-connect-docs_2.13/javadoc.svg)](https://javadoc.io/doc/dev.zio/zio-connect-docs_2.13) [![ZIO Connect](https://img.shields.io/github/stars/zio/zio-connect?style=social)](https://github.com/zio/zio-connect)

Connectors
--------------

Each connector is defined as a separate module and can be used independently or in combination with other connectors.

The following connectors are available. These are submodules and are imported individually:

`zio-connect-couchbase` - Couchbase connector. See [couchbase-connector-examples][couchbase-connector-examples]

`zio-connect-dynamodb` - DynamoDB connector. See [dynamodb-connector-examples][dynamodb-connector-examples]

`zio-connect-file` - Filesystem connector. See [file-connector-examples][file-connector-examples]

`zio-connect-s3` - Amazon S3 connector uses [zio-aws-s3][zio-aws] under the hood. See [s3-connector-examples][s3-connector-examples]


[zio-aws]: https://zio.github.io/zio-aws

[couchbase-connector-examples]: https://github.com/zio/zio-connect/tree/master/examples/couchbase-connector-examples/src/main/scala

[file-connector-examples]: https://github.com/zio/zio-connect/tree/master/examples/file-connector-examples/src/main/scala

[s3-connector-examples]: https://github.com/zio/zio-connect/tree/master/examples/s3-connector-examples/src/main/scala

[dynamodb-connector-examples]: https://github.com/zio/zio-connect/tree/master/examples/dynamodb-connector-examples/src/main/scala

## Documentation

Learn more on the [ZIO Connect homepage](https://zio.dev/zio-connect)!

## Contributing

For the general guidelines, see ZIO [contributor's guide](https://zio.dev/about/contributing).

## Code of Conduct

See the [Code of Conduct](https://zio.dev/about/code-of-conduct)

## Support

Come chat with us on [![Badge-Discord]][Link-Discord].

[Badge-Discord]: https://img.shields.io/discord/629491597070827530?logo=discord "chat on discord"
[Link-Discord]: https://discord.gg/2ccFBr4 "Discord"

## License

[License](LICENSE)
