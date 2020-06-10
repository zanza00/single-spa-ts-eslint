# single-spa-ts-eslint

There is a problem in linting the project, if the file contains only types eslint fails with the following error

```text
yarn run v1.22.4
warning package.json: No license field
$ eslint src --ext js,ts,tsx

/Users/spicciani/dev/microfrontend/single-spa-ts-eslint/src/random/types.ts
  1:13  error  'RandomString' is not defined  no-undef

✖ 1 problem (1 error, 0 warnings)

error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

To replicate install with `yarn` and then run `yarn lint`
