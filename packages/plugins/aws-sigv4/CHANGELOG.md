# Changelog

## 0.1.0
<sub>2026-09-05</sub>

- [#79](https://github.com/seanrobertwright/varlock/pull/79)  *(minor)* Thanks [@app/pull](https://github.com/app/pull)!
  Initial release: adds the aws-sigv4 request-signing scheme to the credential proxy. The agent's AWS SDK signs with placeholder credentials; the proxy re-signs with the real keys, deriving region/service from the request, with optional region/service allowlists.
