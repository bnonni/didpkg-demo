# didpkg-demo

The demo mirror of [didpkg](https://github.com/bnonni/didpkg), on GitHub Pages at https://bnonni.github.io/didpkg-demo/.

- `did.json` is the DID document of `did:web:bnonni.github.io:didpkg-demo`.
- The root is the static mirror (the `DIDPackageRepository` service) of `did:dht:eszfqrywoegyb5grhitsfrybjnce47y5n8j4ec66bgt9r6skmmwy`.
- `web/` is the static mirror of `did:web:bnonni.github.io:didpkg-demo`.

Each publisher must have its own mirror URL, because the mirror path has no DID in it.

`didpkg publish --to dir:<path>` writes the mirror files. Do not edit them by hand: the release signatures cover them.
