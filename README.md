<!-- markdownlint-disable no-inline-html -->

# <div align="center"> catweb-api-info </div>

manually compiled API information used in [catweb](https://www.roblox.com/games/16855862021)'s *webrenderer*

> work in progress! only a readme file currently

## contents

- objects

- properties

- scripting (events & blocks)

- *possibly more in the future*

## usage

all API information is provided as a *single* `api.json` file located in this repository.

> *the `api.json` file is **NOT** a CatWeb script and you **cannot** import it!*

additionaly:

- the `main` branch contains the latest API info for catweb;
- a *new* **Git tag** is created for every *new* version of CatWeb, so you can grab API info for a specific version and compare changes

### option 1: fetch directly (recommended)

API info for the *latest* version:

```plain
https://raw.githubusercontent.com/nekxtari/catweb-api-info/refs/heads/main/api.json
```

API info for a *specific* version:

```plain
https://raw.githubusercontent.com/nekxtari/catweb-api-info/refs/tags/<VERSION>/api.json
```

^ replace `<VERSION>` with the catweb version you need

> the minimum `<VERSION>` available is `v2.13.0.9`. i don't have any API data for older versions of catweb.

### option 2: Git submodule

recommened for projects hosted as Git repositories.

open terminal in your repo and run this:

```bash
git submodule add https://github.com/nekxtari/catweb-api-info
```

(don't forget to push!)

the api will be at the location `catweb-api-info/api.json` in your repository

---

<sup> maintained by [@nekxtari](https://github.com/nekxtari) :) </sup>
