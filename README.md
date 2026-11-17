# policies

Privacy policies, terms and support pages for apps by Julian Ybarra, served by GitHub Pages at
https://julianybarra.github.io/policies/.

One folder per app, each self-contained (its own assets), linked from `index.html`. Spanish is the
default language; English lives under `<app>/en/`.

| App | Home | Privacy | Terms | Support |
|---|---|---|---|---|
| Pull | [/policies/pull/](https://julianybarra.github.io/policies/pull/) | [privacy](https://julianybarra.github.io/policies/pull/privacy/) | [terms](https://julianybarra.github.io/policies/pull/terms/) | [support](https://julianybarra.github.io/policies/pull/support/) |

To add an app: create `<app>/` with `index.html`, `privacy/index.html`, `terms/index.html`,
`support/index.html` (and `en/…` for English), add a row to `index.html` and to this table, push.
Links inside an app folder stay relative, so the folder works anywhere.

Every statement in a privacy policy must match what that app's code does. Change the policy (and
its "Last updated" date) in the same release that changes the behaviour.
