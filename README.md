<p align="center">
  <a href="https://example.com/">
    <img src="https://via.placeholder.com/72" alt="Logo" width=72 height=72>
  </a>

  <h3 align="center">Your Logo here</h3>

  <p align="center">
    Short description
  </p>
</p>

## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Contributing](#contributing)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)

## Quick start

### Installation Guidelines

### Prerequisites

If you don’t havee any of these tools installed already, you will need to:

```
 Download and install git
 Download and install nodejs https://nodejs.org
 Any other tool that your project depends on
```

### Get Started

You will need to clone source code of client GitHub repository. To do this open console and execute following lines:

```shell
git clone https://github.com/[username]/[project-repo].git
```

### Installing Node Modules

You will need to clone source code of client GitHub repository. To do this open console and execute following lines:

```
 cd [project-repo]
 npm install
```

### Running local copy

To run local copy in development mode, execute:

```
 npm start
```

your http://localhost:3000 will be running for API calls

### Setting your environment

The file _.env.dev_ is meant to set the environment variables, _.dev_ is meant to reference the development environment,
If you need to set a new one, make a copy of the same file and rename it to environment you need to work on.
ex: _.env.prod_ .
In which, you'll set the environment variables you need to work on.
To tell express which environment to follow, go to _app.js_
and change the line

```
require('custom-env').env('dev');
```

to

```
require('custom-env').env('prod');
```

## Status

[project-repo] is in developmennt process

## What's included

Here is the folder structure (_change this structure to the structure of your project_)

```text
├───config
|
├───Controllers
|
├───models
|
├───operations
|
├───public
|
├───routes
│   └───api
├───Services
│
├───uploads
|
├───views
```

## Bugs and feature requests

Have a bug or a feature request? Please first read the [issues]() (insert link if available) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](). (insert link if available)

## Contributing

In order to contribute with a feature or User Story in the project you need to create a new branch with your name and the feature name e.g:

```text
branch name : your-name-feature-name
```

Please read through our [Endpoint guidelines](). Included are directions for making an endpoint and notes on development.

Please Read our coding style and contribution [guidelines]().

Moreover, all Javascript should conform to the [Code Guide](), maintained by [standard](https://github.com/standard/standard).

## Thanks

Thanks to the team (list your team mates here)

## Copyright and license

Enjoy :metal:
