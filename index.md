---
nav_exclude: true
---
# Relaycorp Software Documentation

This website hosts the **technical** documentation for some of the [Open Source libraries and applications built by Relaycorp](https://github.com/relaycorp). Of these projects, the following are particularly relevant to **external** stakeholders:

## Awala

Project website: [awala.network](https://awala.network).

- [com.github.relaycorp:awala-endpoint-android](./awala-endpoint-android/): The library that any Android app should use to integrate Awala.
- [Awala-Internet Gateway](./relaynet-internet-gateway/): The gateway that connects Awala private gateways to the Internet.
- [Pong service](./relaynet-pong/): An Internet endpoint for the [Awala Ping Service](https://specs.awala.network/RS-014).

## VeraId

Project website: [veraid.net](https://veraid.net).

- [@relaycorp/veraid](./veraid-js/): The Node.js implementation of VeraId.
- [tech.relaycorp:veraid](./veraid-jvm/): The JVM implementation of VeraId.

## Other

### JavaScript/Node.js projects

- [@relaycorp/object-storage](./object-storage-js/): Unified interface to access major object storage backends (e.g., Amazon S3, Google Cloud Storage, Minio).
- [@relaycorp/dnssec](./dnssec-js/): Resolver-agnostic DNSSEC verification library.
- [@relaycorp/ws-mock](./ws-mock-js/): Mock client and server to unit test the NPM package `ws`.

### JVM projects

- [tech.relaycorp:doh](./doh-jvm/): DNS-over-HTTPS (DoH) client for the JVM and Android.
