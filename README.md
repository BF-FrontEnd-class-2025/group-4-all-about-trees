# All about trees

> This project would be a simple website which is about planting trees.

## Table of contents

- [All about trees](#all-about-trees)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Features](#features)
  - [Status](#status)
  - [Inspiration](#inspiration)
  - [Contact](#contact)
  - [Instructions for use](#instructions-for-use)
  - [Code Quality Checks](#code-quality-checks)
  - [Continuous Integration (CI)](#continuous-integration-ci)
  - [Repo Setup](#repo-setup)

## General info

> A short description

## Screenshots

![Example screenshot](./planning/screenshot.jpg)

## Technologies

- Node 14.16.0
- VSC code
- HTML
- CSS

## Setup

- `npm install`
- `npm run start`

## Code Examples

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>All About Trees</title>

    <meta name="description" content="a short introduction to trees" />
    <meta name="author" content="Team HYF" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />

    <link rel="stylesheet" href="./styles/index.css" />
  </head>

  <body>
    <header class="centered-items">
      <img
        class="bouncy-img"
        src="./assets/happy-tree.jpg"
        alt="a smiling tree"
      />
      <h1>All About Trees</h1>
      <img
        class="bouncy-img"
        src="./assets/happy-tree.jpg"
        alt="a smiling tree"
      />
    </header>
    <nav class="bottom-divider">
      <div class="spaced-items">
        <a href="#summary-info">intro</a>
        <a href="#main-info">content</a>
        <a href="#extra-info">extras</a>
      </div>
    </nav>
    <section id="summary-info">
      <p class="fascinating-words">
        How do Trees Work? Well, this has been a tough question to answer.
        <br />
        My colleagues and I sat down last week and we spent at least 45 minutes
        thinking about it. Still we have nothing smart to say.
      </p>
    </section>
  </body>
</html>
```

```CSS
body {
  background-color: white;
}

.centered-items {
  display: flex;
  flex-direction: row;
  justify-content: center;
  padding-top: 2%;
  padding-bottom: 2%;
}

.bouncy-img {
  width: 5%;
  height: 5%;
}

.bouncy-img:hover {
  animation: bounce 1s;
}

@keyframes bounce {
  0%,
  20%,
  60%,
  100% {
    transform: translateY(0);
  }

  40% {
    transform: translateY(-20px);
  }

  80% {
    transform: translateY(-10px);
  }
}

.bottom-divider {
  border-style: none none solid;
}

.spaced-items {
  display: flex;
  flex-direction: row;
  align-content: center;
  justify-content: space-around;
  padding-top: 2%;
  padding-bottom: 2%;
}

.fascinating-words {
  font-family: fantasy;
}
```

## Features

List of features ready and Todos for future development

- Add java script code
- Add more information
- Add more pictures of trees
- Add more links about trees

To-do list:

- Footer

## Status

Project is: _in progress_

## Inspiration

Project by HYF group-4

## Contact

By [Artur], [Roman], [Manloi], [Almagir]

## Instructions for use

<details>
  <summary>Getting Started</summary>

<!-- a guide to using this repository -->

1. `git clone https://github.com/BF-FrontEnd-class-2025/group-4-all-about-trees.git`
2. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run format:check`: Check to make sure all world spell
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member **_write_** access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Go to _General_ Section > check **Discussions**
- In the _Branches_ section of your repo's settings make sure the
  `master`/`main` branch must:
  - "_Require a pull request before merging_"
  - "_Require approvals_"
  - "_Dismiss stale pull request approvals when new commits are pushed_"
  - "_Require status checks to pass before merging_"
  - "_Require branches to be up to date before merging_"
  - "_Do not allow bypassing the above settings_"

</details>
