# Manato Ogata (@alern-c)

小さな開発ツールを作っています。SQLite / Cloudflare D1 と Cloudflare Workers まわりが中心で、
書くのは Zig・TypeScript・Go が多いです。

## 代表作

### [Qenome](https://github.com/alern-c/Qenome) — インデックスが効くかを、マージ前に確かめる

`npx qenome --d1 DEMO_DB select.sql --suggest` の1コマンドで、候補のインデックスを
サンドボックスのコピー上で比較します。サンプルでは読み取りが 200,000行 → 101行。
元のDBは変更しません。

[![npm version](https://img.shields.io/npm/v/qenome?style=flat-square)](https://www.npmjs.com/package/qenome)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)](https://github.com/alern-c/Qenome/blob/main/LICENSE)
対応: Linux / macOS（x64, arm64）
