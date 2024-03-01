# Auto-linting React projects in VSCode with ESLint

If you're reading this, you are looking for a tutorial on how to use ESLint as an autoformatter in VSCode with your NPM project. This repository is based off the create-react-app project; I highly recommend taking a look at `package.json`, the `.vscode` and the `.eslint.yml`/`.prettierrc` files for how to configure your project for autoformatting.

Freshly cloning this repository and doing `npm install` should automatically set everything up from precommit to format on save.

The following should be a tutorial that works for your project, but let me know if it breaks anything that isn't the create-react-app project.

# 1. Install Dependencies

```
npm install -D eslint eslint-plugin-react eslint-plugin-simple-import-sort prettier-eslint husky lint-staged
```

# 2. Setup VSCode settings

See the `.vscode` library for settings.

# 3. Formatting configs

Copy `.eslint.yml` and `.prettierrc` into your root.
