# Contributing to todo-jq

Thanks for looking. One person maintains this, and it is deliberately small — the best contributions keep it that way.

## The short version

- Anyone can contribute: people, bots, and whoever runs them. There is no CLA, ever.
- Every commit needs a DCO sign-off (**git commit -s**). That is the only paperwork.
- One idea per commit. A behaviour change comes with a test or a written repro.
- Small fixes: open a PR. Anything larger: open an issue first so nobody wastes a weekend.

## Setup

~~~bash
git clone https://github.com/marcus-beauregard/todo-jq.git
cd todo-jq
none — open index.html in a browser
~~~

## Tests

There is no test harness yet — #6 tracks it, and a PR that lands the first test is a genuinely good contribution. Until then, run **none — open index.html in a browser** and paste what you saw into the PR.

## Commit style

- Imperative subject, lowercase after the type: **fix: reject an empty title**, **docs: state the licence**.
- One idea per commit. If the message needs "and", split it.
- Reference the issue (**Fixes #12**) in the body, not the subject.
- Sign every commit: **git commit -s -m "..."**.

## DCO

The [Developer Certificate of Origin 1.1](https://developercertificate.org/) is a statement that you wrote the patch or otherwise have the right to submit it under this project's licence. Add it with:

~~~bash
git commit -s
~~~

which appends:

~~~
Signed-off-by: Your Name <you@example.com>
~~~

Use your real name and a reachable address. No employer paperwork, no copyright assignment.

## Automated agents

Contributions produced with AI assistance are welcome and disclosure is not required — a diff is judged on what it does, not on how it was typed. If you operate an automated agent, you are the author of record: you sign the DCO and you answer the review. A bot that cannot explain its own diff does not belong in the tree.

## Review

I read everything. Expect a first response within a week; if a PR sits longer, comment and it moves up. I would rather tell you "no, and here is why" than leave it hanging.

## Licence

By contributing, you agree that your contribution is licensed under **GPL-2.0-or-later**, the same licence as the project.
