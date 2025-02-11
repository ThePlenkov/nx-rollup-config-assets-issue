# Monorepo Readmee

This is a monorepo readme and not the readme for the project.

It is supposed to be shown in Github, but not in a published package.

## The current issue

Try to run `npx nx build sample` and check built [Readme](dist/sample/README.md)

## Current workaround

Currently it helps to use `__dirname` to get the correct path.

```
assets: [{ input: __dirname, output: '.', glob: '*.md' }],
```
