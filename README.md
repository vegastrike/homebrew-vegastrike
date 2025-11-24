# Homebrew Vega Strike
Homebrew Tap for formula needed to support the Vega Strike Project on MacOS

Vega Strike supports running on MacOS, and our build system builds binaries for MacOS.
For the most part we try to use libraries available via Homebrew as much as we can; but
that is not always possible.

Our goal here is to provide for those edge cases when there is a library we would like
to have in Homebrew for our MacOS builds but it is not yet available. We will be supporting
the library here using licenses compatible with Homebrew. The overall goal is simple:

- Standardize the build process (CI/CD, local builds, etc) as much as possible
- Keep our own code trees clean by utilizing proper package management tooling to install our dependencies
- Support a community driven effort

We ultimately do not want to necessarily own the Homebrew Formula here, and but will
commit to supporting it while its under our care here. If there is interest by the
Homebrew Community or the maintainers of the Projects themselves to take over the
support of the formulas then we will be happy to turn things over to them - just file an issue
on the repository to start the discussion.

In the meantime, we welcome PRs and contributions to these Homebrew formula from all parties
in the spirit of the communities for both Homebrew and Vega Strike.

## Licensing

This repository uses the BSD-2 License just like the Homebrew project does in order to make
it easy for anything here to be adopted by the Homebrew Community should they decide to take it
on.

## Installing

This repository is based on documentation at https://docs.brew.sh/Taps.
Installation should therefore be simple:

```
$ brew tap vegastrike/vegastrike
```

## Homebrew Formula Supported

|  Formula | Purpose | Install |
|----------|---------|---------|
| imgui | ImGui Static library Support | TBD |
