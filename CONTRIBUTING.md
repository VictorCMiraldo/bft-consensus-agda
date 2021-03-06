# Contribution Guide

We welcome your contributions! There are multiple ways to contribute, including filing issues with feedback, bugs and suggestions, as well as contributing code.  See [these guidelines](./TODO.md) for suggestions of things to do and our [Style Guide](STYLE.md) for notes on coding conventions, style, warnings and errors.

## Issues

For bugs or suggestions, please file a GitHub issue unless it's security related. When filing a bug, remember that the better written the bug is, the more likely it is to be fixed. If you think you've found a security vulnerability, do not raise a GitHub issue and follow the instructions on our [Security Policy](./SECURITY.md).

## Contributing code

You will need to sign the [Oracle Contributor Agreement](https://www.oracle.com/technetwork/community/oca-486395.html) (OCA).

For pull requests to be accepted, the bottom of your commit message must have
the following line using the name and e-mail address you used for the OCA.

```text
Signed-off-by: Your Name <you@example.org>
```

This can be automatically added to pull requests by committing with:

```text
git commit --signoff
```

Only pull requests from committers who can be verified as having signed the OCA can be accepted.

### Pull request process

1. Fork this repository
2. Create a branch in your fork to implement your changes. We recommend using
the issue number as part of your branch name, e.g. `1234-fixes`
3. Ensure that any documentation is updated with the changes that are required
by your fix.
4. Ensure that your changes have not broken any existing proofs (`./Scripts/run-everything.sh yes` should complete without errors).
5. Update the list below to include your name if it does not already.
6. Submit the pull request. *Do not leave the pull request blank*. Explain exactly
what your changes are meant to do and provide simple steps on how to validate
your changes. Ensure that you reference the issue you created as well.
7. We will review the pull request before it is merged.

## Contributors

As of the beginning of this repo, contributions have been made by
[Victor Cacciari Miraldo](https://github.com/VictorCMiraldo), [Harold Carr](https://github.com/haroldcarr), [Mark Moir](https://github.com/mark-moir), and [Lisandra Silva](https://github.com/lisandrasilva), all while employed at Oracle Labs.

We are grateful to the following people for contributions since then:
* `[your name here]`

## Code of Conduct

Follow the [Golden Rule](https://en.wikipedia.org/wiki/Golden_Rule). If you'd like more specific guidelines see the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct/).
