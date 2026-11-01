# t3-open

Telegram only allows http(s) links, so this page forwards to a T3 Code deep link. The T3 Code app then opens the thread, on the phone (iOS or Android app) or on the Mac.

```
https://allacher.github.io/t3-open/#<environmentId>/<threadId>  →  t3code://threads/<environmentId>/<threadId>
```

The IDs sit after the `#`, so they're never sent to GitHub. The page is used by [sentry-watch](https://github.com/Allacher/sentry-watch) (private).
