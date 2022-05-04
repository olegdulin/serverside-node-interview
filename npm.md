# How does Node Package Manager Work?

Candidate should be able to describe what npm is and what it does.

## Basics

* What is npm? What does it do?
* What is the difference between `dependencies`, `peerDependencies` and `devDependencies` ? Under what circumstances would you use one over the other?
* What is `package.json` ?
* What is `package-lock.json` ?

## Troubleshooting npm errors

Consider the following error:

```
npm ERR! While resolving: @nrwl/eslint-plugin-nx@12.9.0
npm ERR! Found: @typescript-eslint/parser@4.31.2
npm ERR! node_modules/@typescript-eslint/parser
npm ERR!   dev @typescript-eslint/parser@"~4.31.2" from the root project
npm ERR!   @typescript-eslint/parser@"^4.20.0" from eslint-config-next@11.1.2
npm ERR!   node_modules/eslint-config-next
npm ERR!     dev eslint-config-next@"11.1.2" from the root project
npm ERR!     eslint-config-next@"^11.1.0" from @nrwl/next@12.9.0
npm ERR!     node_modules/@nrwl/next
npm ERR!       dev @nrwl/next@"12.9.0" from the root project
npm ERR!   1 more (@typescript-eslint/eslint-plugin)
npm ERR! 
npm ERR! Could not resolve dependency:
npm ERR! peer @typescript-eslint/parser@"~4.28.3" from @nrwl/eslint-plugin-nx@12.9.0
npm ERR! node_modules/@nrwl/eslint-plugin-nx
npm ERR!   dev @nrwl/eslint-plugin-nx@"12.9.0" from the root project
npm ERR! 
npm ERR! Conflicting peer dependency: @typescript-eslint/parser@4.28.5
npm ERR! node_modules/@typescript-eslint/parser
npm ERR!   peer @typescript-eslint/parser@"~4.28.3" from @nrwl/eslint-plugin-nx@12.9.0
npm ERR!   node_modules/@nrwl/eslint-plugin-nx
npm ERR!     dev @nrwl/eslint-plugin-nx@"12.9.0" from the root project
```

* What does this error mean?
* How do you resolve this error?

See [How to handle conflicting peer dependencies](https://stackoverflow.com/questions/69259024/how-to-handle-conflicting-peer-dependencies) on Stack Overflow.
