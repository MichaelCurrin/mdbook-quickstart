# **Deploy**


## Build

Build your application and generate production-ready output in the ignored `book` directory.

```sh
$ make build
```

That is useful to run locally to check the app builds correctly.


## CI/CD

This project uses GitHub Actions for Continuous Integration / Continuous Deployment.

The flow runs the [Build](#build) command as above then commits the output to the `gh-pages` branch. To serve the site, configure the _Settings_ section of your repo so that GitHub Pages serves the `root` of the `gh-pages` branch.

See the workflow on GitHub:

- [main.yml](https://github.com/MichaelCurrin/mdbook-quickstart/blob/main/.github/workflows/main.yml) file.

See workflow runs here:

- [Actions](https://github.com/MichaelCurrin/mdbook-quickstart/actions) tab.
