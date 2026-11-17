# passwords.today
## Cloudflare publishing

Production uses native Cloudflare Git builds from `master`. Run `npm ci`
and `npm run check:deploy` to validate the explicit public assets directory.
Build with `npm run build` and deploy with `npm run deploy`. Cloudflare holds
deployment credentials; the original Pages branch and source history remain
recovery sources. The revision is at `/.well-known/cloudflare-build.json`.

The published HTML and CSS were copied byte for byte from recovery branch
`gh-pages` commit `9370882c41e2bf20185594659cd52222eaa74674` into `master`; future website edits
for Cloudflare belong on `master`. The recovery branch is unchanged.

## License

Original project code and documentation are licensed under the
[Apache License 2.0](LICENSE). Third-party dependencies, source excerpts,
assets, and other third-party material retain their respective licenses and
copyright notices; this grant does not relicense that material.
