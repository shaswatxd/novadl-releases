# NovaDL Releases

This repo hosts published installers, auto-update manifests, and browser
extension packages for [NovaDL](https://novadl.app) — a modern, fast download
manager for Windows.

The NovaDL application source lives in a private repository. This repo exists
so that:

- The desktop app's auto-updater (`electron-updater`) can check and fetch
  updates via the GitHub Releases API, which requires a public repo for
  unauthenticated access.
- The [landing page](https://novadl.app) download button and release links
  work for anonymous visitors.

No source code is kept here — only release artifacts.

## License

See [LICENSE](./LICENSE).
