> **Archived 2026-10-14.** iloveconference.org no longer runs this proxy. The site is now static files in S3 behind CloudFront, with search on AWS Lambda; see the [client](https://github.com/iloveconference/client) and [server](https://github.com/iloveconference/server) repos.

# simple nginx reverse-proxy for iloveconference

Handles forwarding www to apex domain, compressing results, and adding max expires headers to immutable js and css.

