# kubevue Hooks

Lint files before committing.

## Usage

``` shell
npm i -D husky kubevue-hooks
```

Add following scripts in `package.json`:

``` json
"scripts": {
  "precommit": "node node_modules/kubevue-hooks/precommit"
},
```

Make sure eslint or stylelint installed and `.eslintrc` or `.stylelintrc` in current directory.
