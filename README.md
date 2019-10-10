How to check:

- run `yarn`, you should see `{"version":3,"sources":["../lib-tmp/index.js"],...` in the console - THIS IS INCORRECT
- run `yarn add -D @babel/core@7.5.5`. you should see `{"version":3,"sources":["../src/index.tsx"],...` - this is correct
