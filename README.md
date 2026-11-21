<div align="center">

<img src="assets/logo-512.png" width="96" alt="todo-jq">

# todo-jq

**A todo list in one HTML file. No build step, no dependencies to install.**

[![CI](https://github.com/marcus-beauregard/todo-jq/actions/workflows/ci.yml/badge.svg)](https://github.com/marcus-beauregard/todo-jq/actions/workflows/ci.yml)
[![License: GPL-2.0-or-later](https://img.shields.io/badge/license-GPL--2.0--or--later-blue.svg)](LICENSE)

</div>

## Run it

Open ```index.html``` in a browser. That is the whole install.

To serve it instead — useful on a phone or over a LAN:

```bash
python3 -m http.server 8000
# then http://localhost:8000
```

## What it does

Type a task, press enter, it lands in a list saved to ```localStorage```. A count and a clear-all button sit under the list. Fifty-four lines of HTML, jQuery from a CDN.

## Develop

No build, no test runner. Edit ```index.html```, reload, check the behaviour by hand. Adding a test that drives the file is #2.

## Known gaps

Deleting is immediate with no undo (#9), there are no All/Active/Done filters (#8), tasks cannot be edited (#7), jQuery loads from a CDN without an integrity hash (#4), and a corrupt ```localStorage``` payload blanks the app (#1).

## Contributing

Humans and automated agents are both welcome. There is no CLA — every commit carries a [DCO](https://developercertificate.org/) sign-off (**git commit -s**).

Start with a [good first issue](https://github.com/marcus-beauregard/todo-jq/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22), or read [CONTRIBUTING.md](CONTRIBUTING.md).

## Licence

GPL-2.0-or-later — see [LICENSE](LICENSE). Copyright (C) 2026 Marcus Beauregard.
