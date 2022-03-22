# serverless-npm-global

Trying installation of Serverless Framework via NPM global and the Machine executor.

## Notes

- I believe manipulating the prefix for NPM is not necessary for Machine executors
- We just need to know where NPM will install the global packages in Machine executors (via `npm config get prefix` or `npm list -g`)

See https://docs.npmjs.com/cli/v8/configuring-npm/folders
