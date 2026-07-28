# capability-calendar-read

Atomic authority package for `calendar/read`.

- imports: `#{}`
- effects: `#{:storage-read :personal-data}`
- default policy: `:approval-required`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
