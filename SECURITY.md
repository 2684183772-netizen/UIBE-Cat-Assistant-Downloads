# Security and privacy notes

## v0.1.0 audit summary

- The four release files match the recorded SHA-256 values.
- No private key, signing certificate, GitHub/Coze API token, personal email, local username, WeChat identifier, chat record, or saved application preference was found in the packaged files.
- The packaged application contains only the built Electron/React application, runtime dependencies, icons, and the public Huizhi AI URL.
- Local development credentials and build output directories are ignored by the private source repository and are outside electron-builder's inclusion rules.
- Electron applications necessarily contain executable JavaScript bundles. The public download repository does not contain the private TypeScript source repository.

## Signing status

The v0.1.0 competition build is unsigned and not notarized. Verify the SHA-256 value before running it and keep operating-system security protections enabled.

For security reports, contact the project owner through the competition's official communication channel. Do not include passwords, access tokens, or private personal data in a public issue.
