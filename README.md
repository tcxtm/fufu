# fufu
枫丹大明星
lockfileVersion: '9.0'

settings:
  autoInstallPeers: true
  excludeLinksFromLockfile: false

importers:

  .:
    dependencies:
      cross-env:
        specifier: 7.0.3
        version: 7.0.3
    devDependencies:
      '@commitlint/cli':
        specifier: 19.2.1
        version: 19.2.1(@types/node@22.10.2)(typescript@5.4.3)
      '@commitlint/config-conventional':
        specifier: 19.1.0
        version: 19.1.0
      '@teable/eslint-config-bases':
        specifier: workspace:^
        version: link:packages/eslint-config-bases
      '@types/shell-quote':
        specifier: 1.7.5
        version: 1.7.5
      eslint:
        specifier: 8.57.0
        version: 8.57.0
      husky:
        specifier: 9.0.11
        version: 9.0.11
      lint-staged:
        specifier: 15.2.2
        version: 15.2.2
      npm-run-all2:
        specifier: 6.1.2
        version: 6.1.2
      openapi-typescript:
        specifier: 6.7.5
        version: 6.7.5
      prettier:
        specifier: 3.2.5
        version: 3.2.5
      rimraf:
        specifier: 5.0.5
        version: 5.0.5
      shell-quote:
        specifier: 1.8.1
        version: 1.8.1
      typescript:
        specifier: 5.4.3
        version: 5.4.3
      zx:
        specifier: 7.2.3
        version: 7.2.3

  apps/nestjs-backend:
    dependencies:
      '@ai-sdk/anthropic':
        specifier: 1.0.6
        version: 1.0.6(zod@3.22.4)
      '@ai-sdk/azure':
        specifier: 1.0.13
        version: 1.0.13(zod@3.22.4)
      '@ai-sdk/cohere':
        specifier: 1.0.6
        version: 1.0.6(zod@3.22.4)
      '@ai-sdk/google':
        specifier: 1.0.12
        version: 1.0.12(zod@3.22.4)