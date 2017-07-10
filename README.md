sdx-repo-template
=================

A template git repository for SDX repos:

 - Standardised files for CHANGELOG, CONTRIBUTING, LICENSE and README
 - Default template for Github pull requests

## Getting Started

After creating a new repository on Github, use these commands to initialise it using this template:

```shell
$ git clone git@github.com:ONSdigital/sdx-repo-template <new-repo-name>
$ cd <new-repo-name>
$ git remote set-url origin git@github.com:ONSdigital/<new-repo-name>
```

Then update:

 - **[README](README.md)**
    - Add details appropriate to your new repo (e.g. replace this getting started section!)
    - Update the license date to be the year your repo was created.

 - **[LICENCE](LICENSE)**
    - Update the license date to be the year your repo was created

### Integrations

Integrations that should be set up for your new repository

 - TravisCI
 - Codacy
 - Codecov

## Configuration

An overview of the configuration options available, either as a table of
environment variables, or with a link to a configuration guide.

| Environment variable | Default | Description
| -------------------- | ------- | -----------
| PORT                 | :8080   | The host and port to bind to

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for details.

## License

Copyright (c) 2017 Crown Copyright (Office for National Statistics)

Released under MIT license, see [LICENSE](LICENSE) for details.
