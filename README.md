# logspout - fluentd adapter

This file is a logspout - fluentd adapter for logspout.
Adapter (only) is copied from dsouzajude/logspout-fluentd and improved with ability to retry initial connection to fluentd.

* `CONNECTION_MAX_RETRIES` - how many times to try dial (default 10)
* `CONNECTION_RETRY_WAIT` - time (seconds) between retries (default 1)

For all possible options refer to:
  [logspout](https://github.com/gliderlabs/logspout)
  [logspout-fluentd adapter](https://github.com/dsouzajude/logspout-fluentd)