# Reporting a security problem

If you think you have found a vulnerability in Nyxus, in the console, the receiver, the collectors, the chart, nyxusctl or the registry, please report it privately. Do not open an issue or a discussion for it.

Two ways, either is fine:

- **Report a vulnerability** on this repository's [Security tab](../../security/advisories/new). It is private between you and the maintainer.
- **Email** support@nyxus.co.uk with "security" in the subject.

Say which version (System health names it, and the receiver answers it at `/healthz`), how the deployment runs (Kubernetes or Compose), and what you did. A proof of concept helps; a working exploit against someone else's deployment is not needed and should not be attempted.

## What to expect

- An acknowledgement within three working days.
- A fix in the next release, or a point release for anything that lets data out or in without authorisation. Each release's notes name the security fixes in it, as the 0.6.0 notes do.
- Credit in the notes if you would like it, by whatever name you give.

## Supported versions

A release is supported until the one two after it is published: 0.6.0 is supported until 0.8.0. Security fixes go to the current release. Upgrading is covered in the [knowledge base](https://nyxus.co.uk/kb).

## The security model

How Nyxus holds what it collects, what each part can reach, and what the licence gate does and does not do are published at [nyxus.co.uk/kb-articles/security](https://nyxus.co.uk/kb-articles/security). Every image and chart is signed, and the key and the commands to verify a signature are in the chart's README:

```
helm show readme oci://registry.nyxus.co.uk/nyxus-enterprise/charts/nyxus --version 0.6.0
```
