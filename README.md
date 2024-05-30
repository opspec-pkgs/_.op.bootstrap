[![build](https://github.com/opspec-pkgs/_.op.bootstrap/actions/workflows/build.yml/badge.svg)](https://github.com/opspec-pkgs/_.op.bootstrap/actions/workflows/build.yml)


# Problem statement

Internal op for [opspec-pkgs/maintainers](https://github.com/orgs/opspec-pkgs/teams/maintainers) 
applied to ops (new & existing) to "bootstrap" them w/ latest standards & ops.

includes:
- generation of `README.md` (from op.yml)
- generation of `.opspec` directory
- generation of `.gitignore` file
- generation of `CODEOWNERS` file


# Example usage

## Visualize

```shell
opctl ui github.com/opspec-pkgs/_.op.bootstrap#4.1.2
```

## Run

```
opctl run github.com/opspec-pkgs/_.op.bootstrap#4.1.2
```

## Compose

```yaml
op:
  ref: github.com/opspec-pkgs/_.op.bootstrap#4.1.2
  ## uncomment to override defaults
  # inputs:
  #   srcDir: .
  outputs:
    srcDir:
```

# Support

join us on
[![Slack](https://img.shields.io/badge/slack-opctl-E01563.svg)](https://join.slack.com/t/opctl/shared_invite/zt-51zodvjn-Ul_UXfkhqYLWZPQTvNPp5w)
or
[open an issue](https://github.com/opspec-pkgs/_.op.bootstrap/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see
[project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/main/CONTRIBUTING.md)
