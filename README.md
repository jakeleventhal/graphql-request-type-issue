This is a reproduction of the issue outlined in https://github.com/jasonkuhrt/graphql-request/issues/845

To reproduce:

```bash
pnpm i
cd packages/test/integrations
tsc
```

```
src/index.ts:1:31 - error TS2307: Cannot find module 'graphql-request' or its corresponding type declarations.
  There are types at '/Users/jakeleventhal/Code/graphql-request-type-issue/packages/test/integrations/node_modules/graphql-request/build/entrypoints/main.d.ts', but this result could not be resolved under your current 'moduleResolution' setting. Consider updating to 'node16', 'nodenext', or 'bundler'.

1 import { GraphQLClient } from "graphql-request";
```
