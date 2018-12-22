# asx.com.au API Wrapper

Node.js module to access Australian Securities Exchange
announcements in real-time.

The module allows defining custom patterns to be looked out for in new
announcements, e.g. "CFO resign". The module screens every new announcement,
and checks if any of the defined patterns is included in the announcement.
If a pattern is detected, the module will fire a customisable event.