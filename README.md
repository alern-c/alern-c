# Manato Ogata (@alern-c)

I build small developer tools, mostly around SQLite, Cloudflare D1, and Cloudflare Workers.
I write Zig, TypeScript, and Go.

## Featured

### [Qenome](https://github.com/alern-c/Qenome) — check an index before you merge it

One command compares a candidate index on a sandbox copy of your database:

```sh
npx qenome --d1 DEMO_DB select.sql --suggest
```

In the sample project, rows read drop from 200,000 to 101. The original database is never modified.

[![npm version](https://img.shields.io/npm/v/qenome?style=flat-square)](https://www.npmjs.com/package/qenome)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)](https://github.com/alern-c/Qenome/blob/main/LICENSE)
Linux and macOS (x64, arm64)
