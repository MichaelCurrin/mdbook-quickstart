# **Deploy**


## Build

Build your application and generate production-ready output in the ignored `book` directory.

```sh
$ make build
```

Run that locally to check the app builds correctly. That is also in the CI/CD flow, covered below.


## CI/CD

This project uses GitHub Actions for Continuous Integration / Continuous Deployment.

See the workflow on GitHub:

- [main.yml](https://github.com/MichaelCurrin/mdbook-quickstart/blob/main/.github/workflows/main.yml) file.

See workflow runs here:

- [Actions](https://github.com/MichaelCurrin/mdbook-quickstart/actions) tab.
