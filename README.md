# Zemixo Homebrew Tap

<img src="https://raw.githubusercontent.com/zemixo/homebrew-tap/main/quiet-orbit-banner.svg" alt="Homebrew Tap: A small shelf for useful tools. Zemixo pixel robot workshop." width="100%">

A Homebrew tap for small tools from the Zemixo workshop.

[Availability](#availability) · [Using this tap](#using-this-tap) · [Release policy](#release-policy)

---

## Availability

**claude-agent-ledger 0.7.2** is available from this tap.
The formula installs the checksum-pinned npm source package and uses Homebrew's
`bun` runtime. Installation, fixture checks, and final removal are exercised on
macOS and Linux in CI.

## Using this tap

Install the formula directly; Homebrew adds the tap automatically:

```sh
brew install zemixo/tap/claude-agent-ledger
agent-ledger --version
```

If you have already added this tap, run `brew update` before installing.

The formula reads the same local Claude Code logs as the npm package. Use
`--anonymize` and review subagent and tool names before sharing output.

To remove the installed formula, run `brew uninstall claude-agent-ledger`.
Homebrew may retain its download cache, the Tap checkout, and the shared `bun`
dependency. The formula does not create or remove Claude Code logs.

## Release policy

Formulae should point to stable, checksum-pinned upstream releases. Formula
changes and bottle publication require human review.

See [Homebrew's Tap documentation](https://docs.brew.sh/How-to-Create-and-Maintain-a-Tap)
for trust and installation details.

---

<sub>Made by [Zemixo](https://github.com/zemixo) · Small tools. Made with care.</sub>
