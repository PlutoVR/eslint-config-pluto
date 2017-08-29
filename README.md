eslint-config-pluto
===

Shared eslint configuration.

Installation
---

Available via npm:

`npm install --save-dev eslint-config-pluto`

Usage
---

To use the base configuration, extend `pluto` in a project's `.eslintrc.json`:

```json
{
	"extends": "pluto"
}
```

It is also possible to inherit from `pluto/browser` and `pluto/node`.

Adding Rules
---

- Update the rules
- Run `npm login`.
- Use `npm version` to bump the version.
- Run `npm publish` to publish the new version to npm.
