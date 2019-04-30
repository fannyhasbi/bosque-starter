# Bosque Starter

Simple Bosque experiment programs

> The Bosque programming language is a Microsoft Research project that is investigating language designs for writing code that is simple, obvious, and easy to reason about for both humans and machines. The key design features of the language provide ways to avoid accidental complexity in the development and coding process. The result is improved developer productivity, increased software quality, and enable a range of new compilers and developer tooling experiences.

---

## Development Code

Program files are below the `src/program`

## Building Prepare

In order to build the language the following are needed:

- 64 bit Operating System
- The LTS version of [node.js](https://nodejs.org/en/download/) ( According to your OS )
- Typescript (install with: `npm i typescript -g`)
- Build and test *Bosque* interpreter
  ```
  npm install && npm run-script build && npm test
  ```

## Executing

You can execute by running the `app_runner.js` file followed by the *bosque* program (`.bsq`)

```
node bin/test/app_runner.js FILE.bsq
```

## References

Bosque Programming Language : https://github.com/Microsoft/BosqueLanguage/