# .github

Organisation-wide defaults for [mythicalOS](https://github.com/mythicalOS).

GitHub reads this repository to supply files that individual repositories do not define
themselves. A repository that ships its own copy of any file below overrides the default.

| File | Applies to | Effect |
|---|---|---|
| `profile/README.md` | — | Renders the public organisation landing page at `github.com/mythicalOS` |
| `SECURITY.md` | every repo | Vulnerability reporting policy |
| `CONTRIBUTING.md` | every repo | Contribution rules, including the DCO sign-off requirement |
| `CODE_OF_CONDUCT.md` | every repo | Contributor Covenant 2.1 |
| `SUPPORT.md` | every repo | Where to ask questions |
| `.github/ISSUE_TEMPLATE/*.yml` | every repo | Issue forms shown in the issue chooser |
| `.github/ISSUE_TEMPLATE/config.yml` | every repo | Disables blank issues; adds contact links |
| `.github/PULL_REQUEST_TEMPLATE.md` | every repo | Default pull request body |

Defaults reach **public and private** repositories in the organisation. Contributors outside
the organisation only ever see the ones on repositories they can access.

## Editing

Changes take effect as soon as they land on `main` — there is no build or deploy step. The
organisation profile page can take a few minutes to reflect an edit to `profile/README.md`.

Licensed under Apache-2.0. See [LICENSE](LICENSE).
