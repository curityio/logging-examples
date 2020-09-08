# Logging Examples

[![Quality](https://img.shields.io/badge/quality-demo-red)](https://curity.io/resources/code-examples/status/)
[![Availability](https://img.shields.io/badge/availability-source-blue)](https://curity.io/resources/code-examples/status/)

This repo includes examples of how you can configure and control logging in the Curity Identity Server.

## Per-client Debug Logging

This example shows how to create per-client debug logging in a safe and secure way. Refer to the writeup on the Curity Web site for more details. The [log4j2 configuration file](per-client-debug-logging-log4j2.xml) includes a full working example. It calls out the changes that would need to be made compared to the currently-delivered default version of the configuration file. In particular, take note of these changes:

* The `PatternLayout` of the request log
* The addition of the `debug-log` appender 
* The `RequestReceiver` logger
* The changes to the root logger

For more details, refer to the full writeup.

## Lnav Add-on

You may also be interested in the [lnav plug-in](https://github.com/curityio/lnav) for parsing Curity-related log files.

## Other Samples

Not finding what you're looking for? Please let us know if some other logging-related sample would be helpful, and we'll see about adding it here. In the meantime, check out the [product documentation](https://developer.curity.io/docs/latest/system-admin-guide/logging/index.html) on logging.

## License

The code and samples in this repository are licensed under the [Apache 2 license](LICENSE).

## Questions

For questions and comments, contact Curity AB:

> info@curity.io
> https://curity.io

Copyright (C) 2020 Curity AB.
