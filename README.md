# puppet-module-cookiecutter-template

A [cookicutter](https://cookiecutter.readthedocs.io/) template that helps
bootstrapping a new Puppet module.

It includes:
* Module metadata
* Base file hierarchy
* A Gemfile with base dependencies
* A [rspec](http://rspec.info/) configuration that handles default facts,
  and coverage
* A [Travis](https://travis-ci.org/) configuration for CI and automated
  deployment on [Puppet Forge](https://forge.puppet.com/)
* A base README.md with badges

## Usage

```bash
cookiecutter https://github.com/pmuller/puppet-module-cookiecutter-template.git
```
