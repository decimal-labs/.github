# Contributing

Thanks for taking the time. This is the organization-wide default — **if the repository you are
working in has its own `CONTRIBUTING.md`, that one wins.** The spec repositories
([agentversion](https://github.com/decimal-labs/agentversion),
[skillevaluation](https://github.com/decimal-labs/skillevaluation)) in particular have a slower,
more deliberate process, because a specification that changes casually is not much of a
specification.

## Before you write code

For anything beyond a typo or an obvious one-line fix, **open an issue first**. It costs you five
minutes and it saves you the version of this where you write something good and we say "ah, we're
about to change that whole area." We would rather agree on the shape of a change before you spend
an evening on it.

Small, self-contained fixes — a broken link, a wrong type hint, an off-by-one in a docstring — go
straight to a pull request. No ceremony needed.

## Pull requests

- **One change per PR.** A PR that fixes a bug and also reformats forty files is a PR nobody can
  review honestly.
- **Say what breaks if you are wrong.** The most useful line in a PR description is usually the one
  describing the failure mode you are preventing.
- **Add a test that fails without your change.** If the change is genuinely untestable, say so in
  the description and explain why — that is a legitimate answer, but it should be a considered one.
- **Run the repository's own checks before pushing.** Every repo documents its test command in its
  README or CI workflow; use that rather than guessing.
- **Keep the diff honest.** Don't reformat code you aren't otherwise touching, and don't let your
  editor reflow files on save.

## Reporting bugs

Open an issue with what you expected, what happened, and the smallest thing that reproduces it.
Version numbers help a lot — for the Python packages, `pip show decimalai` (or the relevant
package) tells you what you're on.

**If it's a security issue, don't open an issue.** See [SECURITY.md](./SECURITY.md).

## Licensing

By contributing you agree that your contribution is licensed under the same license as the
repository you are contributing to. That is Apache-2.0 for the specification repositories, MIT for
the libraries and tooling, and CC-BY-4.0 for documentation prose. Each repository's `LICENSE` file
is authoritative.

## Conduct

Everything here happens under our [Code of Conduct](./CODE_OF_CONDUCT.md). It is the ordinary
version of this: be decent, assume good faith, and take disagreements to the substance rather than
the person.
