# @dominicbarnes/eslint-config-test

> Adds ESLint configuration for use in mocha test environments.

## Usage

In a `test/.eslintrc`, add the following:

```
{
  "extends": "@dominicbarnes/test"
}
```

**NOTE:** this will probably be renamed into `@dominicbarnes/mocha` if I end up adopting other test
frameworks and need to distinguish between them. (but since I always use mocha, there's no reason
for that yet)
