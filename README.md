# roster-releases

Public releases of Roster, a macOS app for Git worktrees and the Claude Code and Codex sessions tied to them.

- **Download:** the latest zip is under [Releases](https://github.com/jpitchell/roster-releases/releases/latest). Unzip it, then move `Roster.app` to `/Applications`.
- **Updates:** Roster checks [`appcast.xml`](appcast.xml) through Sparkle and installs new versions itself. Choose **Roster > Check for Updates…** to check now.
- **What changed:** [CHANGELOG.md](CHANGELOG.md).

Everything here is written by `make release` in the Roster source repo. Don't edit `appcast.xml` by hand: every entry carries an EdDSA signature over its zip.
