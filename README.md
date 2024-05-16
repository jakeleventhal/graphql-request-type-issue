This is a reproduction of the issue outlined in https://github.com/jasonkuhrt/graphql-request/issues/845

To reproduce:

```bash
pnpm i
cd packages/test/integrations
tsc
```

```
▶ tsc
src/index.ts:1:31 - error TS2307: Cannot find module 'graphql-request' or its corresponding type declarations.

1 import { GraphQLClient } from "graphql-request";
                                ~~~~~~~~~~~~~~~~~


Found 1 error in src/index.ts:1
```
