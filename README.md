# lxicon

A tree-shakable colorful SVG icon library.

## Release Checklist

Before every release:

1. Update the `version` in `package.json`.
2. Run `npm publish`.

## Current Publish Settings

- Package name: `@chogng/lxicon`
- Publish scope: public package
- Publish config: `publishConfig.access = public`

## Notes

- `prepublishOnly` already runs `npm run build`, so `npm publish` will rebuild automatically.
- You do not need to run `npm login` as part of the normal release flow if your npm auth is already available.
- If npm returns `EOTP`, your account has 2FA enabled. Complete the one-time password flow, then publish again.
