# .github

Shared Renovate preset for ping-poet and activescott repos. It lives in `default.json`.

A repo uses it by adding `"extends": ["github>ping-poet/.github"]` to its `renovate.json`.

This repo is public on purpose: Mend's Renovate app can't read a private preset across accounts.
