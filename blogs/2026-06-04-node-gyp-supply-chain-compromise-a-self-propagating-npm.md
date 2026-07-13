---
title: "Node-gyp Supply Chain Compromise: A Self-Propagating npm Worm That Hides in binding.gyp"
url: "https://snyk.io/blog/node-gyp-supply-chain-compromise-self-propagating-npm-worm-binding-gyp/"
date: "2026-06-04"
feed_url: "https://snyk.io/blog/feed/"
---
A new npm worm is abusing binding.gyp to trigger node-gyp during install, letting malicious packages run code without lifecycle scripts. It steals credentials, persists in GitHub, and self-propagates across maintainers.
