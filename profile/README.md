<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kollaudo/kollaudo/main/docs/assets/title-dark.svg">
    <img src="https://raw.githubusercontent.com/kollaudo/kollaudo/main/docs/assets/title.svg" alt="Kollaudo" width="460">
  </picture>
</p>

<p align="center">
  <strong>Quality gates for every promotion, whatever builds, tests and deploys your software.</strong>
</p>

Your tests already run somewhere: GitHub Actions, Azure DevOps, a Kargo verification, a tester's laptop.
Kollaudo collects their results, and before a version moves on it gives one honest answer:

- ✅ **pass**: every test that had to run, ran and passed
- ❌ **fail**: something broke, and here's the run with the failing test
- 🤷 **unknown**: the tests never reported, so it doesn't go anywhere either

It never builds, tests or deploys anything. It just judges, politely ✨

```bash
kollaudo push ctrf-report.json --component api --env staging --version 3f2a9c1
kollaudo verdict --component api --env staging --version 3f2a9c1   # exit code 0, 1 or 2
```

### Start here

- 🧭 **[kollaudo/kollaudo](https://github.com/kollaudo/kollaudo)**: the project, with a five-minute [quick start](https://github.com/kollaudo/kollaudo#quick-start)
- 📮 **[Sending test results](https://github.com/kollaudo/kollaudo/blob/main/docs/sending-results.md)** from any framework and any CI
- 📦 **[`ghcr.io/kollaudo/kollaudo`](https://github.com/kollaudo/kollaudo/pkgs/container/kollaudo)** and **[`@kollaudo/cli`](https://www.npmjs.com/package/@kollaudo/cli)** on npm

Kollaudo is young and open source (Apache-2.0). Ideas, questions and "it didn't work for me" are all
welcome in [Issues](https://github.com/kollaudo/kollaudo/issues).

[One minute overview](https://lnkd.in/p/egSXMh5b)
