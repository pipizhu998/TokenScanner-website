# TokenScanner project website

Website source for [TokenScanner](https://pipizhu998.github.io/TokenScanner/).
The research code lives in [pipizhu998/TokenScanner](https://github.com/pipizhu998/TokenScanner).

## Publishing

After pushing website changes to this repository's `main` branch, run
[Publish project page](https://github.com/pipizhu998/TokenScanner/actions/workflows/pages.yml)
in the code repository using **Run workflow**. The workflow reads this repository's
latest `main` and publishes it at the existing website URL.

Alternatively, use:

```sh
gh workflow run pages.yml --repo pipizhu998/TokenScanner --ref main
```

Pushing website changes here does not publish them automatically.
